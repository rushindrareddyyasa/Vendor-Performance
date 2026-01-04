# Vendor Performance Analysis Dashboard

## Project Overview
This project analyzes vendor and brand performance using sales, purchase, inventory, and profitability data.
A complete data pipeline was built using Python, SQL (SQLite), and Power BI.

## Tech Stack
- Python (Pandas, SQLAlchemy)
- SQLite
- Jupyter Notebook
- Power BI
- Git & GitHub

## Workflow
1. Raw CSV ingestion into SQLite database
2. SQL-based aggregation and joins
3. Feature engineering (profit margin, stock turnover, performance score)
4. Vendor & brand performance analysis
5. Interactive Power BI dashboard

## Key Insights
- Identified top and low-performing vendors
- Analyzed purchase contribution concentration
- Derived performance score using business metrics

## Dashboard
Power BI dashboard visualizes:
- Total sales, profit, margin KPIs
- Top vendors and brands
- Low performing vendors
- Contribution analysis

## How to Run
1. Run `ingestion.py` to load raw data
2. Run `get_vendor_summary.py` to generate summary tables
3. Open notebooks for analysis
4. Open `dashboard.pbix` in Power BI Desktop
