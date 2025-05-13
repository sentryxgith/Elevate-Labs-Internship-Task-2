# Elevate-Labs-Internship-Task-2

# Superstore Sales Analysis

## Overview

This project analyzes the [Superstore dataset](https://www.kaggle.com/datasets/arpitagupta11/superstore-csv) to uncover key business insights using data cleaning, preprocessing, and interactive visualizations. The workflow includes data cleaning in Python, exploratory data analysis, and dashboard creation in Power BI.

---

## Table of Contents

- [Overview](#overview)
- [Data Cleaning](#data-cleaning)
- [Visualization & Insights](#visualization--insights)
- [Key Findings](#key-findings)
- [How to Use](#how-to-use)
- [Repository Structure](#repository-structure)
- [Credits](#credits)

---

## Data Cleaning

**Performed in Python (see `data_cleaning.py`):**
- Checked for and handled missing values (none found).
- Removed duplicate rows.
- Renamed columns to lowercase with underscores.
- Converted date columns (`order_date`, `ship_date`) to datetime format.
- Ensured correct data types for numeric columns (`sales`, `profit`, `quantity`, `discount`).
- Saved the cleaned data as `cleaned_superstore.csv`.

**Summary Table:**

| Step                | Action Taken                          |
|---------------------|---------------------------------------|
| Missing Values      | None found                            |
| Duplicates          | Removed                               |
| Text Standardization| All object columns standardized       |
| Column Renaming     | Lowercase, underscores                |
| Date Conversion     | order_date, ship_date to datetime     |
| Numeric Types       | Ensured for sales, profit, etc.       |

---

## Visualization & Insights

**Created in Power BI (`Superstore_Dashboard.pbix`):**

- **Sales Trends Over Time:** Line chart (by month & category)
- **Profit by Segment:** Pie chart
- **Top Customers by Sales:** Horizontal bar chart
- **Sales by Category & Segment:** Stacked bar chart
- **Sales vs. Profit:** Scatter plot
- **Discount Impact on Profit:** Waterfall chart (steps: sales, discount, profit)
- **Regional Performance:** Interactive slicer/filter

**Dashboard Screenshot:**  
![Screenshot 2025-05-13 224330](https://github.com/user-attachments/assets/47337473-cd31-4bc6-b54c-6a3384d60991)

---

## Key Findings

- **Sales are rising**, led by the Technology category.
- **Profitability is highest in Technology**; Furniture lags behind.
- **Top 10 customers drive a significant portion of sales**.
- **Discounts reduce profit margins**, especially in Furniture.
- **West region outperforms others** in both sales and profit.

---

## How to Use

1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/superstore-analysis.git
   ```
2. **Data Cleaning**
   - Run `data_cleaning.py` to clean the raw Superstore data.
3. **Visualization**
   - Open `Superstore_Dashboard.pbix` in Power BI Desktop to explore the interactive dashboard.

---

## Repository Structure

```
├── Superstore Analysis Dashboard.pdf
├── Superstore Sales & Profit Analysis.pptx
├── TASK 2 DATA ANALYST.pdf
├── cleaned_superstore.csv
├── data_cleaning.py
├── README.md
```

---

## Credits

- Dataset: [Kaggle Superstore CSV](https://www.kaggle.com/datasets/arpitagupta11/superstore-csv)
- Data Cleaning & Analysis: Suraj Rajeshkumar Rajvanshi
- Dashboard: Suraj Rajeshkumar Rajvanshi
