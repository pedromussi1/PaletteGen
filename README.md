# PaletteGen

A free, client-side color palette generator. Create harmonious palettes, extract colors from images, and export as CSS, Tailwind, or SVG.

## Features

- **Harmony Mode** — Generate palettes based on color theory: Analogous, Complementary, Triadic, Split Complementary, Tetradic, Monochromatic
- **Random Mode** — Golden ratio hue distribution for visually pleasing random palettes
- **Image Extraction** — Upload an image and extract dominant colors using k-means clustering
- **Lock Colors** — Lock individual swatches to keep them while regenerating the rest
- **Adjustable Count** — Generate 3 to 10 colors per palette
- **Shareable Links** — Palette encoded in URL hash for easy sharing
- **Export** — Copy as CSS variables, Tailwind config, or download as SVG
- **Dark/Light Theme** — Toggle with button or `T` key

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Space` | Generate new palette |
| `T` | Toggle theme |
| Click swatch | Copy hex color |

## Tech Stack

- Vanilla HTML/CSS/JavaScript — zero dependencies, no build step
- Client-side only — no data sent to any server

## Run Locally

Open `index.html` in your browser. No install needed.

## License

MIT
