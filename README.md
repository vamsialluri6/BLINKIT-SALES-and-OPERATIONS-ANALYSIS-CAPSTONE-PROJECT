# BLINKIT-SALES-and-OPERATIONS-ANALYSIS-CAPSTONE-PROJECT

A comprehensive end-to-end data analytics project for Blinkit—an e-grocery delivery platform—featuring Power BI, SQL Server, Python, and Excel integration. This project walks through data cleaning, KPI analysis, business insights, and dashboard reporting.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Tech Stack](#tech-stack)
- [Workflow](#workflow)
- [How to Use](#how-to-use)
- [Results and Insights](#results-and-insights)
- [Contact](#contact)

## Project Overview

- **Objective:** Deliver actionable business insights for Blinkit’s sales and outlets using a modern analytics toolkit.
- **Approach:** Start from raw CSV import → Clean in SQL/Python → Analyze KPIs and sales trends → Visualize in Power BI and Excel.
- **Portfolio Focus:** End-to-end demonstration of data engineering, analytics, and dashboarding skills.

## Dataset

- **Source:** Blinkit store transaction data (`blinkit_data.csv`)
- **Rows:** 8,523 transactions
- **Columns:** 12, including:
    - `item_identifier` – Product code
    - `item_fat_content` – Fat content (cleaned: "Low Fat", "Regular")
    - `item_type` – Product category (fruit, drinks...etc.)
    - `item_weight` – Weight per item
    - `item_visibility` – In-app promotion score
    - `outlet_identifier` – Store code
    - `outlet_location_type` - Tier 1/2/3
    - `outlet_establishment_year` – Store launch year
    - `outlet_size` – Small/Medium/Large
    - `outlet_type` – City tier / format
    - `sales` – Sales amount
    - `rating` – Customer rating

## Tech Stack

- **Data Storage/Processing:** Microsoft SQL Server
- **Scripting/Analysis:** Python (pandas, numpy)
- **Visualization:** Power BI, Microsoft Excel

## Workflow

1. **Data Import**
    - Load `blinkit_data.csv` into SQL Server.
    - Confirm row and column integrity.
2. **Data Cleaning**
    - Fix categories (e.g., "LF" → "Low Fat").
    - Assign correct data types.
    - Handle missing values.
3. **Analysis**
    - Compute KPIs: total sales, average sale, items sold, avg. rating.
    - Analyze by fat content, category, outlet type, year, size, etc.
4. **Visualization**
    - Power BI dashboards: interactive KPIs, breakdowns, trend analysis.
    - Excel pivots for cross-checking and static sharing.
5. **Advanced Analytics**
    - Python for additional transformation or custom metrics if needed.

## How to Use

### Requirements

- Microsoft SQL Server & Management Studio
- Python 3.x (with pandas, numpy)
- Power BI Desktop
- Microsoft Excel

### Steps
1. Place `blinkit_data.csv` in the `/data` directory.
2. Follow `/sql/import.sql` to create tables and import data.
3. Run `/sql/datacleaning.sql` to clean and standardize.
4. Build dashboards in `/powerbi/` and create reports in `/excel/`.

## Results and Insights
- Sales and rating leaders identified by product and outlet.
- Outlets and product types with low performance flagged for action.
- Business recommendations for operational improvement presented via dashboards.

## Contact
Project Owner: VAMSI ALLURI  
Email: vamsialluri2004@gmail.com 
