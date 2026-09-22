# ZenEarth Renewables — Website

Static, dependency-free homepage (plain HTML/CSS, no build step). Desktop and mobile are
two separate DOM sections toggled by a CSS media query at 767px — the fastest way to ship
both approved designs as one deployable site.

## Files
- `index.html` — the page
- `styles.css` — all styling, including the responsive breakpoint
- `assets/` — the solar/wind showcase videos + poster images

## Run locally
Just open `index.html` in a browser, or serve it:
```
npx serve .
```

## Known placeholders to fill in before going live
- Footer contact block: `[City], India`, `[contact email]`, `[phone]`
- Nav links "Sectors", "About", "Insights" point to `#` (no pages built yet)
- "Talk to us" buttons link to `#contact` (an in-page anchor) — wire up a real form or mailto when ready
