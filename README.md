# Corey Jeansonne Designs — redesign concept

A responsive, static example website with a forest green, green-gray, and light sage identity. Hosted with GitHub Pages; no build step or server dependencies.

## Included

- CJ drafting-sheet monogram and a standalone brand direction page.
- Home, Portfolio, Floor Plans, and Contact views with hash navigation.
- All 12 portfolio designs re-rendered as photorealistic 4:5 portrait images, with the entire home framed for the vertical gallery. An accessible native-dialog gallery supports category filtering, previous/next navigation, arrow keys, swipe, and original/enhanced comparison.
- New home visualization based on the original elevation, and a reconstructed contact-page kitchen image.
- All 60 original floor-plan cards, specifications, and prices. The November 2 revision adds a dedicated 4:5 portrait re-render for every home; the original source files remain in assets. Cards are display-only. Search, bedroom/bathroom/size filters, reset, and progressive loading run locally.
- A 104-pixel desktop logo, 22-pixel studio wordmark, 17-pixel desktop navigation, 18-pixel body copy, and larger plan numbers, prices, and specifications. Featured cards share matching top edges and caption baselines.
- Responsive layouts for desktop, tablet, narrow folded devices, and wide unfolded devices; safe-area and viewport-segment spacing; reduced-motion support.
- Demo contact form validates locally and sends/stores nothing.

## Preview locally

Run `python -m http.server 4174` in this directory, then open `http://localhost:4174`.

## Publish

In GitHub Settings → Pages, publish from `main` and `/ (root)`. `.nojekyll` disables Jekyll processing. All asset paths are relative and work below a GitHub Pages project path. Navigation uses hashes to avoid deep-link 404s.

## Sources and assets

Content, contact information, plan data, and original imagery: https://www.coreyjeansonnedesigns.com/ (retrieved November 2, 2026).

The built-in `image_gen` tool created the logo and enhanced imagery. `asset-provenance.json` records sources and the prompt set. AI-generated visualizations may vary in fine details and are labeled as visualizations. The concept project titles describe imagery and are not asserted client/project names.

Typography: Manrope and DM Sans via Google Fonts, with system fallbacks. Logo: `assets/cj-mark.png` (transparent PNG). Colors and typography: `brand.html` and CSS variables in `style.css`.

This is a redesign demonstration, with no checkout, plan purchasing, backend form submission, or active plan-detail links.
