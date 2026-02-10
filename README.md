# CellGenius — Projects Roadmap & Capacity Planner

A fully client-side Project Portfolio Management (PPM) web application. No server required — runs entirely in your browser.

## Features

- **Excel Import/Export** — Upload your Roadmap Tracker Excel file directly in the browser (reads .xlsx, .xlsm, .xls)
- **Project Editor** — Edit projects, RICE scoring, MoSCoW classification, team allocations
- **Gantt Chart** — Interactive timeline with drag-to-reschedule, team capacity overlay
- **Roadmap Generator** — Auto-optimize project scheduling based on RICE scores and team capacity
- **Analytics Dashboard** — Charts for coverage, significance, division, status distributions
- **Team Capacity Planning** — FTE allocation per project with over-capacity warnings
- **Saved Versions** — Save and load roadmap snapshots locally
- **JSON Import/Export** — Full data portability between sessions and users
- **Data Persistence** — LocalStorage auto-save (survives browser refresh)

## Quick Start

1. Open the app URL (or `index.html` locally)
2. Click **📂 Upload Excel** to load your Roadmap Tracker file
3. All changes are auto-saved in your browser
4. Use **💾 Export Excel** or **📋 Export JSON** to download your data

## Deployment (GitHub Pages)

1. Create a new GitHub repository
2. Push these files to the `main` branch
3. Go to **Settings → Pages → Source** → select `main` / `/ (root)` → Save
4. Your app will be live at `https://<username>.github.io/<repo-name>/`

## Files

| File | Description |
|------|-------------|
| `index.html` | Complete application (single-file, self-contained) |
| `logo.png` | CellGenius brand logo |

## Technology

- Pure HTML/CSS/JavaScript — no build step
- [SheetJS](https://sheetjs.com/) for in-browser Excel parsing
- [Chart.js](https://www.chartjs.org/) for analytics charts
- LocalStorage for data persistence
