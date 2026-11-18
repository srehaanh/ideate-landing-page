# Techfest IIT Bombay: An Aetherial Renaissance

A concept landing page for Techfest 2026, themed **An Aetherial Renaissance**. It is a single-page experience with no build step, 3D assets or JavaScript libraries. Google Fonts are loaded online.

## Run locally

Open `index.html` in a recent browser. The page uses a small gzip loader around the original self-contained HTML to keep the GitHub Contents upload compact; the browser decodes it at runtime. An internet connection is needed for Google Fonts.

## Deploy with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Select **Deploy from a branch**.
3. Choose branch `main` and folder `/(root)`, then save.

## Design and interactions

- Renaissance notebook / aether concept with lapis-lazuli blue, gold-leaf and vellum palette; Bodoni Moda display type.
- Hero armillary sphere draws itself on load. A cursor-following lens reveals hidden annotations; touch devices get an autonomous lens movement.
- Stars and sphere move at different speeds for parallax.
- Live countdown to 16 December 2026 (IST).
- Scroll-reactive history timeline.
- Filterable competition cards for AI, Robotics, Drones and Sustainability.
- Expandable Workshops, Speaker Sessions and Exhibitions panels.
- Magnetic buttons, custom cursor, scroll progress bar, keyboard focus styling and reduced-motion support.

## Customize

The original page is a self-contained HTML document with embedded CSS and JavaScript. Change the date in the countdown variable `T`, challenge data in array `C`, panel content in `PN`, and colours in the `:root` CSS variables.

## Content note

This is a concept landing page. The uploaded source README states some date information is sourced from a third-party guide and advises confirming dates and rules on the official Techfest website. Review factual event details before using the page publicly.
