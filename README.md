# Rooter

Back it. Root it. Get paid.

The Rooter website. One static page, no build step: `index.html` holds the markup, styles and script. `brand/` holds the logo kit and X assets. `assets/` holds the social preview image.

- Live: https://rootrprotocol.github.io/rooter-site/
- Whitepaper: https://rooter-3.gitbook.io/whitepaper/

## Editing

Edit `index.html` and push to `main`. GitHub Pages redeploys in about a minute.

Three links are placeholders until the values exist: elements with `data-pons-link`, `data-x-link` and `data-contract`. Set them in one place at the bottom of `index.html`.

## Custom domain

1. Add a `CNAME` file at the repo root containing the domain, for example `rooter.xyz`.
2. At the registrar, add four `A` records for the apex pointing at `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`, and a `CNAME` record for `www` pointing at `rootrprotocol.github.io`.
3. In the repository settings under Pages, enter the domain and turn on Enforce HTTPS once the certificate is issued.
