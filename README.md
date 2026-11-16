# Vyant website

Static single-page site for Vyant, served from `index.html`. No build step.

## Publish with GitHub Pages

1. Repository Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
2. Custom domain: `vyant.ai` (already set in the `CNAME` file).
3. At your DNS provider, point the apex domain at GitHub Pages with A records
   185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153,
   and add a CNAME record for `www` pointing to `<owner>.github.io`.
4. Once DNS resolves, tick "Enforce HTTPS".

## Before launch

- Connect the demo request form to a CRM or form backend (it currently shows a notice and sends nothing).
- Replace the illustrative API snippet under Resources with the published reference.
