# Subscription-Cohort-Analysis

## Purpose

Power BI dashboard for visualizing monthly subscriber retention rates via cohort analysis. Tracks customer lifecycle from signup through cancellation.

## How to Open

Open `Subscription Cohort Analysis.pbix` in Power BI Desktop.

## Data

- `Subscription Cohort Analysis Data.csv` — source dataset (customer_id, created_date, canceled_date, subscription_cost, subscription_interval, was_subscription_paid)
- `Subscription Cohort Analysis Data Dictionary.csv` — field definitions

## Key Rules

- **Raw data must not be modified.** The CSV files are the source of truth. All transformations happen within Power BI.
- This is a Power BI project, not a code project. There is no build step or test suite.
- Do not introduce external tooling or scripts unless explicitly instructed.
- Secrets must never be hardcoded.
