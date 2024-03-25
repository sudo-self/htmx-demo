## <a href="https://htmx.jessejesse.com">htmx-demo&nbsp;[![Deploy static content to Pages](https://github.com/sudo-self/htmx-demo/actions/workflows/static.yml/badge.svg)](https://github.com/sudo-self/htmx-demo/actions/workflows/static.yml)
![Screenshot 2024-03-24 at 10 07 39 PM](https://github.com/sudo-self/htmx-demo/assets/119916323/2d522693-7565-4d76-a9f9-17ccda92720b)
![Screenshot 2024-03-24 at 10 08 13 PM](https://github.com/sudo-self/htmx-demo/assets/119916323/7fef1e85-0409-45ea-b2fa-8c1f5007d17d)

```s

//htmx CDN

<script src="https://unpkg.com/htmx.org/dist/htmx.js"></script>

//htmx button

<button id="load-more-button" hx-get="/page2.html" hx-swap="afterend" hx-target="#additional-content" class="button-64 mt-8">HTMX</button>

//event listener

 document.getElementById('load-more-button').addEventListener('click', function() {
            this.click();
        });
```
