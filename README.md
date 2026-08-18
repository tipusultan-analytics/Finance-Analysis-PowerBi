# Finsite Bank — Finance Analytics Dashboard

**Power BI | DAX | Time Intelligence | Data Modeling | Dashboard Design**

An end-to-end Power BI finance analytics project built for a fictional bank, "Finsite Bank," covering the full workflow: data collection, cleaning, modeling, DAX measure design, and dashboard build-out.

## Dashboard Previews



![Customer Finance](customer%20finance.jpeg)





![Transaction](transaction%20(1)

.png)

## Problem Statement / Objective

- Give banking stakeholders a single, interactive view of transaction volume, value, fees, and tax collected across years, regions, and customer segments.
- Show year-on-year (YoY) growth or decline for every core metric.
- Let users dynamically switch the underlying metric driving the charts.
- Support root-cause investigation via drill-through with export to CSV.

## Tools & Data Source

- **Tool:** Microsoft Power BI Desktop
- **Data:** Transactions table and customers table spanning 2023–2026
- **Supporting table:** A dedicated Calendar/Date table for time-intelligence calculations

## Key DAX Measures

For each of the 5 core KPIs: a base measure, a previous-year version using `SAMEPERIODLASTYEAR()`, and a YoY growth % measure.

## Skills Demonstrated

- **DAX:** `CALCULATE`, `SUM`, `AVERAGE`, `DISTINCTCOUNT`, `DIVIDE`, `SAMEPERIODLASTYEAR()`
- **Data modeling:** relating multiple tables
- **Interactivity:** drill-through navigation, filtered CSV export, multi-level slicers

## Repository Contents

- `finance analysis.pbix` — Power BI project file
- `finance_transactions.csv` / `customers finance analysis.csv` — source data
- `finace analysis project report.docx` — full project write-up
- `business requirements finance analysis.docx` — business questions
- `Finance-Analytics ppt.pptx` — presentation deck
