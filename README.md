# HTML over DNS over HTTPS (aka. HoDoH)

HoDoH is a 'specification' for hosting HTML pages and reading them with the help of DNS over HTTPS (DoH). That means that there is nothing hosted anywhere but on all the DNS servers in the world.


Simply add some TXT records to your domain and just read them.

DNS example from wille.io:
```
IN TXT "<br />Plus if you add TXT entries one after another, you can split your HTML to bypass the 255 character limit.</body></html>"
IN TXT "<html><body>This is an HTML site, hosted by my DNS provider and is not hosted anywhere else."
```

Try it here with the domain 'wille.io': https://wille-io.github.io/html-over-dns-over-https/?l=wille.io

Replace 'wille.io' at the end with the domain name from which you want to read HTML from.
