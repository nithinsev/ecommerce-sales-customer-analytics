# E-Commerce Sales Analysis using Python

## Project Overview

This project focuses on analyzing an e-commerce sales dataset using Python to understand sales performance, product performance, customer purchasing patterns, payment preferences, and revenue trends.

The analysis uses data cleaning, data manipulation, aggregation, and visualization techniques to identify meaningful business insights from the dataset.

## Objectives

- Analyze overall e-commerce sales performance.
- Identify the best-selling and highest revenue-generating products.
- Analyze revenue across different product categories.
- Identify cities contributing the highest revenue.
- Understand customer purchasing patterns.
- Analyze payment method preferences.
- Identify monthly revenue trends.
- Present business insights through data visualizations.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Dataset Information

- **Dataset:** E-Commerce Sales Dataset
- **Total Records:** 1,500
- **Total Original Columns:** 10
- **Time Period:** January – December 2025
- **Data Type:** Synthetic Practice Dataset

### Dataset Columns

| Column | Description |
|---|---|
| Order_ID | Unique order identifier |
| Order_Date | Date of the order |
| Customer_ID | Customer identifier |
| Product | Product name |
| Category | Product category |
| Quantity | Number of units purchased |
| Unit_Price | Price per unit |
| Discount_Percent | Discount applied |
| Payment_Method | Payment method used |
| City | Customer's city |

## Data Analysis Process

### 1. Data Loading & Exploration
- Imported the required Python libraries.
- Loaded the CSV dataset using Pandas.
- Examined the dataset using `head()`, `shape`, and `info()`.

### 2. Data Cleaning
- Checked for missing values.
- Identified duplicate records.
- Converted the order date column into datetime format.
- Created a new Revenue column after applying discounts.

### 3. Sales Analysis
- Calculated total revenue and total quantity sold.
- Identified the best-selling product.
- Identified the highest revenue-generating product.
- Analyzed category-wise and city-wise revenue.
- Calculated Average Order Value (AOV).

### 4. Customer & Payment Analysis
- Identified top revenue-generating customers.
- Analyzed payment method usage.
- Compared revenue across payment methods.

### 5. Time-Based Analysis
- Analyzed monthly revenue trends.
- Identified the highest and lowest revenue months.

### 6. Data Visualization
- Monthly revenue trend line chart.
- Category-wise revenue bar chart.
- Category revenue contribution pie chart.
- City-wise category sales heatmap.

## Key Business Insights

| Metric | Result |
|---|---|
| Total Orders | 1,500 |
| Total Quantity Sold | 3,017 |
| Total Revenue | ₹39,09,178.55 |
| Average Order Value | ₹2,606.12 |
| Best Selling Product | Desk Lamp |
| Best Selling Product Quantity | 182 units |
| Highest Revenue Product | Coffee Maker |
| Highest Product Revenue | ₹4,92,493.10 |
| Top Revenue Category | Home & Kitchen |
| Category Revenue | ₹13,58,425.90 |
| Top Revenue City | Delhi |
| City Revenue | ₹4,86,816.75 |
| Most Used Payment Method | UPI |
| UPI Transactions | 625 |
| Highest Revenue Month | March |
| Monthly Revenue | ₹3,93,124.15 |

## Project Outcome

This project demonstrates how Python can be used for data cleaning, exploratory data analysis, grouping, aggregation, and visualization.

The analysis helped identify important sales patterns, top-performing products, revenue-generating categories, customer trends, and monthly performance.

It provides practical experience in using Python libraries for data analysis and converting raw data into meaningful business insights.

## Conclusion

The project successfully analyzed 1,500 e-commerce order records and generated useful insights into sales performance and customer purchasing behavior.

It strengthened practical knowledge of Python, Pandas, NumPy, and data visualization techniques.

## Disclaimer

This project uses a synthetic dataset created for educational and analytical practice. The results do not represent actual business transactions.