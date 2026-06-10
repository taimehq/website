# taime-website

Marketing site for [Taime](../taime), the native multi-agent coding workspace.

Static site, no build step: `index.html` + `styles.css` + `script.js`.
Design tokens (ink surface ladder, warm off-white text, accent blue, Geist /
Geist Mono) are lifted from the app's `tailwind.config.js` so the site looks
like the product. Fonts load from the jsDelivr Fontsource CDN.

## Develop

```bash
python3 -m http.server 4173
# → http://localhost:4173
```

## Deploy

Any static host (GitHub Pages, Cloudflare Pages, Netlify, Vercel) — point it
at the repo root, no build command.

## TODO

- Wire the two `href="#"` placeholders in the CTA (`Download for macOS`,
  `View on GitHub`) to the real release artifact and repo URL.
- Add an `og:image` (a capture of the hero window works well).
