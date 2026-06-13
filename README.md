# Wushu Chen Academic Homepage

Static academic homepage for Cloudflare Pages.

## Local Preview

Open `index.html` directly in a browser, or run a local static server:

```bash
python3 -m http.server 8787
```

## Cloudflare Pages

- Build command: leave empty
- Build output directory: `.`
- Production branch: `main`

The site can also be deployed directly with Wrangler:

```bash
wrangler pages deploy . --project-name personal-academic-homepage --branch main
```
