# Odyssey Works — Website

Front-facing marketing site for **Odyssey Works Inc.** — board-level advisory at the
convergence of AI, blockchain infrastructure, and digital assets.

A single-page static site. No build step, no framework, no dependencies — just
`index.html`, local fonts, and the logo.

## Structure

```
odyssey-works-site/
├── index.html          # the entire site (HTML + CSS + JS inline)
├── assets/
│   ├── logo.png        # brand mark / favicon
│   └── fonts/          # Space Grotesk + Space Mono (self-hosted woff2)
└── README.md
```

## Run locally

It's a static file — open `index.html` directly, or serve the folder:

```bash
# Python
python -m http.server 8000

# or Node
npx serve .
```

Then visit `http://localhost:8000`.

## Deploy

Any static host works. Point it at the repo root:

- **GitHub Pages** — Settings → Pages → deploy from branch (root).
- **Netlify / Vercel / Cloudflare Pages** — drag-and-drop the folder, or connect
  the repo. No build command; publish directory is the root.

## Notes

- Fonts and the logo are self-hosted, so the site renders fully offline.
- The media library embeds **YouTube** video thumbnails and click-to-play players,
  which load from `youtube.com` / `ytimg.com` at view time (needs internet).
- All content is in `index.html`. Sections: Hero · About · Why Odyssey · Practices ·
  Experience · Pipeline · Library · Contact, plus a keyword-matching chat assistant.

## Contact

- Web: schedule via the in-page "Schedule a consultation" button
- Email: ceo@odyssey-works.io
- X: [@Aces1974](https://x.com/Aces1974) · LinkedIn:
  [/in/jerryfragiskatos](https://www.linkedin.com/in/jerryfragiskatos/) · Telegram:
  [@satoshigreek](https://t.me/satoshigreek)

---

© 2026 Odyssey Works Inc.
