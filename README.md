# Ravencraft Paranormal Investigations

Marketing site for **Ravencraft Paranormal Investigations** — a family-run, evidence-based
paranormal (ghost & haunting) investigation service. On-site nationwide, remote worldwide.

A single self-contained `index.html` (no build step, no dependencies) hosted on GitHub Pages.

**Live:** https://werth-code.github.io/ravencraft-paranormal/

## Editing

Everything lives in `index.html` — HTML, CSS, and JS in one file. Fonts load from Google Fonts;
the fog and waveform are `<canvas>` effects that respect `prefers-reduced-motion`.

Common edits:
- **Contact info** — search for `intake@ravencraftparanormal.com` and `(802) 555-0146` (placeholders).
- **Copy** — sections are commented (`<!-- hero -->`, `<!-- story -->`, etc.).

## Intake form

The form is currently front-end only: it validates, then hands the visitor a pre-filled
`mailto:` and a copy button. To deliver submissions to an inbox, wire the form to a backend
(e.g. a Cloudflare Worker, Formspree, or Netlify Forms).
