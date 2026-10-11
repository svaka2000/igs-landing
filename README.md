# iOS GPS Spoofer — landing page

Marketing site for [iOS GPS Spoofer](https://github.com/renyifan2009-hash/iOS-GPS-Spoofer-V1.1.1), a macOS app that sets an iPhone's location using Apple's developer location simulation.

**Live:** https://igs-landing-phi.vercel.app

## What this is

A single-page static site — one `index.html` with inline CSS/JS plus a handful of image assets. No framework, no build step.

## Run locally

```bash
python3 -m http.server 8787
# then open http://localhost:8787
```

Or just open `index.html` in a browser.

## Deploy

Hosted on Vercel. `vercel.json` sets a few security headers and long-lived caching for `/assets`.

```bash
vercel deploy --prod
```

## Notes

- Type: Bricolage Grotesque (display) + Geist / Geist Mono. Warm-paper palette with an Apple-blue accent and automatic dark mode (`prefers-color-scheme`).
- The product it describes uses Apple's developer location simulation — the same mechanism as Xcode's "Simulate Location." It's reversible and installs nothing on the iPhone.
- Map data © OpenStreetMap contributors.
