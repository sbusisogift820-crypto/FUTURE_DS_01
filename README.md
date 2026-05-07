# FUTURE_DS_01
Online Retail Sales Performance Analysis
Future Interns - Data Analytics Internship: Task 1

Project Overview
This project involves a comprehensive analysis of transactional data from an online retail store. The goal was to transform raw data into actionable business intelligence by identifying sales trends, high-value products, and regional performance.

I implemented a full data pipeline—from cleaning and transformation in Python to structured querying in SQLite and interactive visualization.

Tech Stack
Language: Python 3.x

Libraries: Pandas, Matplotlib, Seaborn, Plotly

Database: SQLite3

Environment: Google Colab / Jupyter Notebook

Data Pipeline & Methodology
Data Cleaning: * Removed rows with missing CustomerID to ensure accurate behavior tracking.

Filtered out negative Quantity and UnitPrice values (handling returns/errors).

Standardized InvoiceDate to datetime objects for time-series analysis.

Database Integration: * Migrated the cleaned dataset into a SQLite database (OnlineRetail.db).

Used SQL queries to aggregate data, demonstrating the ability to handle structured data in a production-like environment.

Visualization (The Dashboard): * Developed a "Client-Ready" dashboard to visualize growth and product rankings.

Key Insights & Results
1. Revenue Trends
The analysis shows significant growth patterns, particularly during the end-of-year holiday season.

2. Product Performance
I identified the top 10 products contributing to the majority of the total revenue. This allows for optimized inventory management.

3. Executive Summary
Total Revenue: [$8,911,407.90]

Total Successful Orders: [18536]

Average Order Value: [$22.39]

Business Recommendations
Inventory Scaling: Increase stock for the identified Top 10 products at least 2 months prior to the Q4 holiday spike.

Customer Retention: Launch targeted loyalty campaigns in the highest-performing regions to maintain momentum during slower months.
