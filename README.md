# LIONEL MESSI — The Eternal Archive

An interactive, single-page tribute to Lionel Andrés Messi. Explore the milestones, records, and defining moments of his career through a visual archive built with semantic HTML and modern CSS, no JavaScript or build tools required.

## Highlights

- **Five career eras:** switch between Argentina, FC Barcelona, Paris Saint-Germain, Inter Miami, and Messi's Rosario and La Masia beginnings. The selected era updates the page's colors and displayed career profile.
- **Iconic goals:** explore four illustrated goal trajectories on an SVG pitch and open a tactical dossier for each moment.
- **Career records:** view a breakdown of Messi's 91-goal calendar year in 2012.
- **Trophy vault:** interact with CSS-powered 3D cards for his Ballon d'Or and European Golden Shoe achievements.
- **Career timeline:** expand milestone chapters from his early years through the Argentina and Miami eras.
- **Responsive visual design:** a bento-style dashboard, era-themed color tokens, and a World Cup background image adapt across screen sizes.

## Get started

View the live site at <https://messi-eternal-archive.vercel.app/>.

No installation, dependencies, or build step are needed to run the project locally. Clone or download the repository and open `index.html` in a modern browser.

## Project structure

MESSI-ETERNAL-ARCHIVE
├── index.html
├── messi-wc22.png
└── css/
    ├── 01-tokens-themes.css
    ├── 02-base-layout.css
    ├── 03-tactical-pitch.css
    ├── 04-3d-trophies.css
    └── 05-timeline-scroll.css

The CSS files are loaded in order from `index.html`:

1. `01-tokens-themes.css` — shared design tokens and era-specific themes.
2. `02-base-layout.css` — page styling, layout, and record visualizations.
3. `03-tactical-pitch.css` — pitch, goal trajectories, and popover dialogs.
4. `04-3d-trophies.css` — interactive trophy-card effects.
5. `05-timeline-scroll.css` — timeline styling and scroll-driven effects.

## Built with

- **HTML5** for the page structure, era controls, native popovers, and expandable timeline.
- **CSS3** for layouts, theme switching, animation, and 3D effects.
- **Inline SVG** for the football pitch and flag icons.

The page has no JavaScript. It uses modern browser features including CSS `:has()`, the HTML Popover API, and named `<details>` accordions. Scroll-driven timeline animation is progressively enhanced where supported; for the best experience, use an up-to-date browser.

## Content note

Career statistics and descriptions are editorial content embedded in the page, not live data. Some figures may change or require verification; check authoritative sources before relying on them.

## Disclaimer

This is an independent fan-made tribute and is not affiliated with or endorsed by Lionel Messi, his representatives, or any football club or governing body.
