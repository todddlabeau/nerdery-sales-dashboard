# Nerdery Sales Pipeline Dashboard — 2026

A single-file HTML dashboard for the Nerdery sales pipeline weekly review.

## Features

- **Dashboard tab** — KPI cards, goals vs actuals, pipeline trend chart, rep/vertical/stage breakdowns
- **Pipeline Detail tab** — Sortable, filterable table of all active opportunities with next steps
- **MBANT Qualification tab** — Per-opportunity MBANT scoring with expandable detail

## Hosting

Deployed to Google Cloud Storage:
`https://storage.googleapis.com/nerdery-sales-dashboard/index.html`

## Data

All data is embedded in `index.html`. To update, modify the `OPPS`, `MBANT_OPPS`, and `DASH` constants in the `<script>` section.
