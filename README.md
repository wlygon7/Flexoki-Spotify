# Flexoki — Spicetify/Spotify Theme

An inky, warm Spotify theme based on [Steph Ango's Flexoki](https://stephango.com/flexoki) color palette.

> "Like ink on paper." — Flexoki is designed for legibility and perceptual balance.

## Preview
![Flexoki Dark Preview](preview.png)

## Schemes
- **Dark** — warm dark backgrounds, muted tones, red/orange accents
- **Light** — paper whites, ink blacks, earthy accent colors

## Installation via Marketplace
1. Open Spotify with Spicetify installed
2. Go to **Marketplace** in the sidebar
3. Search **Flexoki**
4. Click **Install**

## Manual Installation
```bash
cd "$(spicetify -c | xargs dirname)/Themes"
git clone https://github.com/wlygon7/spicetify-flexoki Flexoki
spicetify config current_theme Flexoki color_scheme Dark
spicetify apply
```

## Attribution
Flexoki palette by [Steph Ango](https://stephango.com/flexoki) — MIT License