
# Data Documentation

## Required datasets

This project uses three CSV datasets.

| Filename | Purpose |
|---|---|
| epl_model_dataset.csv | Historical EPL match data and engineered features |
| england-premier-league-matches-2025-to-2026-stats.csv | 2025/26 results for Elo reconstruction |
| england-premier-league-matches-2026-to-2027-stats.csv | 2026/27 results and upcoming fixtures |

## Data preparation

The historical dataset covers eight Premier League seasons, from 2018/19 to 2025/26.

The current-season dataset contains completed matches used to calculate team form and update Elo ratings.

The upcoming fixtures dataset supplies the Matchweek 11 fixtures and other future matches.

## Important

The CSV datasets are not included in this repository.

Users must obtain the datasets from their original sources and ensure they have the appropriate permissions before using or redistributing them.

Place the files in the location expected by the notebook, or update the notebook's file paths accordingly.

## Reproducibility

The forecasting notebook documents the data preparation, feature engineering, Elo calculations, model evaluation and Matchweek 11 probability forecasts.
