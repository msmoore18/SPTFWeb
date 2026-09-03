# Spruce Point Farm Map

Interactive tree farm inventory map for Spruce Point. Click any lot on the map to explore its inventory breakdown by size and grade.

## Features

- **Satellite basemap** with color-coded lot polygons (density-based)
- **By Size tab** — inventory breakdown across all 27 size classes (12" through 25')
- **By Row tab** — per-row inventory with all sizes as columns
- **Year selector** — toggle between 2024 and 2025 fall inventory data
- **Farm-wide totals** in the header, split by year
- PWA-ready: installable on mobile and desktop

## Data

Inventory is loaded at runtime from Fall Inventory Summary CSVs in the repo root (not embedded in the page).

- **2025 season (current):** `2025-2026_Fall_Inventory_Summary_8_4_26_by_row.csv` — Fall 2026 counts with C grades removed (31,857 A+B trees).
- **2024 season:** `2024-2025 Fall Inventory Summary 3.24.25_by_row.csv`

The live site is [sptf.starmesaproperties.com](https://sptf.starmesaproperties.com/). GitHub Pages serves the `main` branch root.

## Deployment

This site is deployed via [GitHub Pages](https://pages.github.com/). The `main` branch root is served as the site.

To deploy your own copy:
1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://<username>.github.io/<repo-name>/`
