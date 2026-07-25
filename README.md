# Vishal Kumar Puri — Portfolio

A single-page, dependency-free portfolio site for a Machine Learning Engineer / Data Scientist / Data Analyst working on production ML systems for smart-city infrastructure (SCADA telemetry, complaint SLA prediction, energy forecasting).

**Live site:** _add your GitHub Pages / Vercel / Netlify link here_

## Highlights

- **Dark, systems-console aesthetic** — dashboard-style UI (amber/teal on near-black) that mirrors the AVEVA OMI / SCADA environments the projects run against.
- **Live inference console** — a typing-effect terminal in the hero that cycles real-looking prediction calls (`/predict/sla-breach`, ARIMA forecasts, anomaly flags).
- **Hand-built SVG data visualizations** for each flagship system:
  - Forecast-vs-actual load curve with anomaly marker (energy analytics)
  - Feature-importance bar chart + precision/recall/F1 cards (SLA breach classifier)
  - Before/after downtime benchmark by sector (borewell efficiency)
- **Animated, count-up stats** and skill-proficiency bars, all triggered on scroll via `IntersectionObserver`.
- **Fully responsive**, no build step, no external JS framework — pure HTML/CSS/vanilla JS.

## Tech

| | |
|---|---|
| Markup / styling | HTML5, CSS custom properties, no CSS framework |
| Fonts | Space Grotesk (display), IBM Plex Sans (body), IBM Plex Mono (data/labels) |
| Interactivity | Vanilla JS — scroll reveals, count-up counters, animated bars, typewriter console |
| Charts | Hand-authored inline SVG (no chart library / no external requests) |
| Hosting | Static — works on GitHub Pages, Netlify, Vercel, or any static host |

## Project structure

```
.
├── index.html    # everything — markup, styles, and script in one file
└── README.md
```

## Running locally

No build step required.

```bash
git clone https://github.com/vviiishu/<repo-name>.git
cd <repo-name>
open index.html   # or just double-click it / use a live-server extension
```

## Deploying to GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select the branch (usually `main`) and root folder.
4. Save — your site will be live at `https://<username>.github.io/<repo-name>/`.

## Customizing

- **Colors / type scale** — all defined as CSS custom properties at the top of `index.html` under `:root`.
- **Chart data** — the system charts use illustrative SVG coordinates matched to the stated metrics (forecast accuracy, feature importance, downtime reduction). Swap in real values from your trained models if you want the charts to be literally, not just plausibly, accurate.
- **Avatar** — the "VP" monogram in the hero is a placeholder; replace the inline `<svg>` block with an `<img>` tag pointing to a real headshot if you'd like.
- **Content** — experience, systems, projects, skills, and education are all plain HTML blocks; no CMS or data file to manage.

## Contact

- Email: [vpuri4055@gmail.com](mailto:vpuri4055@gmail.com)
- LinkedIn: [vishal-kumar-puri](https://www.linkedin.com/in/vishal-kumar-puri-846ba5288)
- GitHub: [@vviiishu](https://github.com/vviiishu)
- Novypro: [vishalkumar-puri](https://www.novypro.com/profile_projects/vishalkumar-puri)

## License

Personal portfolio — feel free to reference the structure, but please don't reuse the content/copy as your own.
