Pizza Sales Data Analysis Project
This project analyzes a year's worth of pizza store sales data to identify key business indicators. The primary goal is to provide actionable insights for menu optimization and operational efficiency. 

1. Project Overview
This project analyzes a year's worth of sales data for a fictional pizza restaurant chain to uncover key business insights. By processing and visualizing data from over 48,000 orders, the project identifies trends in customer behavior, operational bottlenecks, and opportunities for revenue growth.
2. Business Objectives
The analysis focuses on answering critical business questions:
Peak Hours & Days: When is the store busiest, and how does this affect staffing?
Menu Optimization: Which pizzas are the best and worst sellers by revenue and quantity?
Performance Metrics: What is the average order value and seasonality of sales?
3. Key Performance Indicators (KPIs)
Calculated using SQL queries:
Total Revenue: Sum of all pizza prices.
Average Order Value: Total revenue divided by total orders.
Total Pizzas Sold: Sum of quantities sold.
Total Orders: Distinct count of order IDs.
Average Pizzas Per Order: Total pizzas sold divided by total orders.
4. Technical Tools Used
Data Extraction & Transformation: SQL (MySQL/PostgreSQL) for cleaning and aggregating raw CSV data.
Data Exploration: Python (Pandas/Seaborn) for exploratory data analysis (EDA).
Interactive Visualization: Power BI or Tableau to create dynamic dashboards.
5. Key Insights & Findings
Based on typical analysis of this dataset (e.g., Kaggle Pizza Sales):
Busiest Time: Orders peak between 12:00 PM – 1:30 PM and 6:00 PM – 8:00 PM.
Top Days: Sales are highest on Fridays and Saturdays.
Popular Choice: The Classic Deluxe Pizza is frequently the top seller by quantity.
Revenue Driver: Large (L) size pizzas contribute the most to total revenue.
6. Project Structure
text
├── data/               # Raw and cleaned datasets (CSV/XLSX)
├── sql_queries/        # SQL scripts for KPIs and data cleaning
├── dashboards/         # Power BI dashboard files
└── README.md           # Project documentation
