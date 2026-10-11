# Retail Sales Analysis

**A Beginner Data Analytics Portfolio Project using Python, Pandas, and Matplotlib**

## Project Overview

This project analyzes a fictional retail sales dataset covering January to March 2026. The goal is to calculate key business metrics, identify sales and profit trends, compare product categories and cities, and provide data-driven business recommendations.

> **Dataset Notice:** This is fictional practice data created for learning and portfolio purposes. It does not represent a real business.

## Business Objectives

- Calculate total sales, cost, profit, and profit margin.
- Compare performance across product categories and cities.
- Identify the month with the highest sales.
- Analyze product revenue and units sold.
- Communicate findings through visualizations and recommendations.

## Tools and Technologies

- **Python** — data analysis
- **Pandas** — data cleaning, calculations, and aggregation
- **Matplotlib** — data visualization
- **Jupyter Notebook / Google Colab** — development environment
- **GitHub** — project version control and portfolio

## Dataset

The dataset contains 18 records and 8 original columns.

| Column | Description |
|---|---|
| `Order_ID` | Unique order identifier |
| `Order_Date` | Date of the order |
| `City` | City where the order was placed |
| `Category` | Product category |
| `Product` | Product name |
| `Quantity` | Units sold |
| `Unit_Price_PKR` | Selling price per unit |
| `Unit_Cost_PKR` | Cost per unit |

The analysis creates additional columns for sales, total cost, and calculated profit.

## Key Performance Indicators (KPIs)

| Metric | Result |
|---|---:|
| Total Sales | PKR 117,300 |
| Total Cost | PKR 92,870 |
| Calculated Profit | PKR 24,430 |
| Overall Profit Margin | 20.83% |
| Total Orders | 18 |
| Units Sold | 73 |
| Average Order Value | PKR 6,516.67 |

## Key Findings

### 1. Category Performance

- **Furniture** generated the highest sales at PKR 71,600 and the highest calculated profit at PKR 13,300.
- Furniture had the lowest category profit margin at 18.58%.
- **Electronics** achieved the highest category profit margin at 26.01%.
- Office Supplies sold the most units, with 36 units.

### 2. Monthly Sales Trends

| Month | Sales |
|---|---:|
| January 2026 | PKR 28,200 |
| February 2026 | PKR 50,850 |
| March 2026 | PKR 38,250 |

- **February recorded the highest monthly sales**, reaching PKR 50,850.
- Sales increased by **80.32%** from January to February.
- Sales decreased by **24.78%** from February to March.

### 3. City Performance

- **Lahore** recorded the highest sales at PKR 49,200 and the highest calculated profit at PKR 9,070.
- Faisalabad achieved the highest city-level profit margin at 24.88%.

### 4. Product Performance

- **Office Chair** generated the highest product sales at PKR 50,000 and calculated profit of PKR 8,800.
- **Notebook Pack** had the highest sales volume, with 23 units sold.

## Methodology

1. Loaded the CSV dataset using Pandas.
2. Inspected the dataset structure, data types, missing values, duplicates, and date values.
3. Calculated sales, total cost, and profit.
4. Calculated business KPIs, including total sales, profit margin, and average order value.
5. Grouped data by category, month, city, and product.
6. Created charts to compare performance and identify trends.
7. Interpreted the results and developed business recommendations.

## Business Formulas

**Sales**

`Sales = Quantity × Unit Price`

**Total Cost**

`Total Cost = Quantity × Unit Cost`

**Calculated Profit**

`Profit = Sales − Total Cost`

**Profit Margin**

`Profit Margin (%) = Profit ÷ Sales × 100`

**Average Order Value**

`AOV = Total Sales ÷ Number of Unique Orders`

## Business Recommendations

- **Furniture:** Investigate product costs and pricing because this category generates the highest sales but has the lowest category profit margin.
- **Electronics:** Study the pricing and cost factors behind its higher profit margin.
- **City performance:** Examine Lahore's strong sales and Faisalabad's higher margin to identify practices that may be useful elsewhere.
- **Monthly monitoring:** Collect more months of data before making long-term trend or forecasting decisions.
- **Future analysis:** Include discounts, returns, shipping, and operating expenses for a more complete financial picture.

## Visualizations

The Jupyter Notebook contains charts for comparing:

- Sales by product category
- Monthly sales trends
- Sales by city
- Product performance
- Other relevant business summaries

Open the notebook to view the charts and supporting calculations.

## Project Files

- [Jupyter Notebook](./Retail%20Sales%20Analysis.ipynb)
- [Dataset (CSV)](./retail_sales.csv)
- [Analysis Report (PDF)](./retail_sales_analysis_report%20%281%29%20%281%29.pdf)

## How to Run the Project

1. Clone or download this repository.
2. Open `Retail Sales Analysis.ipynb` in Jupyter Notebook or Google Colab.
3. If using Google Colab, upload `retail_sales.csv`. If using local Jupyter, place the CSV in the notebook's working directory.
4. Make sure the CSV path in the code matches the file location.
5. Run the notebook cells in order.

## Limitations

- The dataset contains only 18 records.
- The data is fictional and intended for practice.
- Calculated profit is based on sales minus product cost; it is **not net profit** because operating expenses, taxes, shipping, and returns are not included.
- Three months of data are insufficient to establish reliable long-term trends or seasonality.
- The analysis identifies patterns but does not establish their causes.

## Conclusion

This project demonstrates foundational data analytics skills, including data inspection, validation, calculation of business KPIs, grouping and aggregation with Pandas, visualization with Matplotlib, and communicating findings through actionable recommendations.

It is a beginner-level portfolio project intended to demonstrate the process of turning raw sales data into understandable business insights.

---

**Author:** Muneeb Waince  
**Project:** Retail Sales Analysis  
**Skills:** Python, Pandas, Matplotlib, Data Cleaning, Exploratory Data Analysis, KPI Analysis, Data Visualization
