# Electricity Time Series Forecasting (15-Minute Intervals)

📄 [PDF Report](./electricity-time-series.pdf)

🌐 [Project page](https://nikolailen.github.io/electricity-time-series/)

👤 Project contact: [Nikolai Len](https://www.linkedin.com/in/niklen/)

Forecast electricity consumption for a single target day (96 points at 15-minute frequency) using historical electricity demand and temperature data.

Author: Nikolai Len  
Data ScienceTech Institute, 2025

Language: R

## Repository Overview

- `index.md`: GitHub Pages-ready report.
- `index_files/`: figures used by `index.md`.
- `electricity-time-series.Rmd`: source analysis report.
- `electricity-time-series.pdf`: final cleaned PDF report.
- `consumption_15min_train.xlsx`: input dataset.
- `*.rds`: pretrained forecasting models.

## Notes

- All data/model paths in the R Markdown report use relative paths.
- Models are already pretrained and stored in this repository.
- No retraining is required to review the main results in `index.md` and `electricity-time-series.pdf`.

## GitHub Pages

Use `index.md` at repository root as the published project page.

## License

This project is licensed under the MIT License. See [LICENSE](./LICENSE).
