# Veera Kumar | Portfolio

> Terminal-themed personal portfolio — [veerakumar.com](https://veerakumar.com)

## Sections

- **Boot Loader** — Fake system initialization on load
- **Hero** — Profile intro with cycling role titles (Cloud Support Engineer, DevOps, etc.)
- **About** — Bio with expandable terminal-card
- **Resume** — Timeline (education + experience) + animated skill bars
- **Portfolio** — Project carousel with dot navigation and auto-scroll
- **Utilities** — App launcher cards for stock analysis & financial tools
- **Contact** — Phone, email, LinkedIn
- **404** — Terminal-themed "Command Not Found" page

## Built With

- [Astro](https://astro.build) 6 — Static site generation
- Vanilla CSS — Terminal aesthetic, responsive, dark/light themes
- Vanilla JS — Boot animation, intersection observers, carousel, theme toggle

## Project Structure

```
src/
├── components/     # Astro components
│   ├── BootLoader.astro
│   ├── Navbar.astro
│   ├── Hero.astro
│   ├── About.astro
│   ├── Resume.astro
│   ├── Portfolio.astro
│   ├── Utilities.astro
│   └── Contact.astro
├── pages/
│   ├── index.astro
│   └── 404.astro
└── styles/
    └── global.css
public/
├── favicon.png
└── robots.txt
```

## Commands

| Command                 | Action                           |
| ----------------------- | -------------------------------- |
| `npm install`           | Install dependencies             |
| `npm run dev`           | Dev server at `localhost:4321`   |
| `npm run build`         | Static site build → `dist/`      |
| `npm run preview`       | Preview production build locally |

## Deploy

1. `npm run build`
2. Copy `dist/*` into `theveerakumar.github.io`
3. Commit and push the GitHub Pages repository

## Utilities

| App | Path | What it does |
| --- | ---- | ------------ |
| **Stockalysis** | `/stockalysis/` | Technical analysis dashboard — RSI, MACD, SMA/EMA, Bollinger Bands, Pivot Points, Fibonacci levels |
| **StockVedic** | `/stockvedic/` | NSE stock dashboard — real-time quotes, historical charts, fundamentals (Screener.in), entry zone guidance, analyst consensus |
| **Seaborn** | `/seaborn/` | Financial calculators — rental yield, EMI, affordability |
