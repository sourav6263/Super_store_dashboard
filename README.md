# Super_store_dashboard

📊 Super Store Sales Dashboard – Power BI Project
📝 Project Overview
This project presents a comprehensive Power BI dashboard designed for a fictional Super Store, providing insights into key business metrics like sales, profit, customer segments, and geographic performance. The dashboard enables data-driven decision-making by offering clear visualizations and KPIs to stakeholders.

📦 Dataset Used
Superstore Sales Data
The dataset contains transactional-level data including:

Order ID, Customer Name, Region, Segment

Product Category and Sub-Category

Sales, Quantity, Discount, Profit

Shipping Mode and Dates

📌 Key Features of the Dashboard
✅ Sales Performance Overview

Total Sales, Profit, and Quantity sold

Year-over-Year trends and seasonality

🌍 Regional and State-Level Insights

Profitability heatmaps by state

Sales by region and city

📦 Product Analysis

Top and bottom-performing categories/sub-categories

Sales and profit contribution per product type

👥 Customer Segmentation

Segment-wise analysis (Consumer, Corporate, Home Office)

Customer lifetime value and contribution to revenue

📅 Time Intelligence

Monthly/Yearly comparisons

Use of DAX functions like DATEADD(), DATESYTD(), etc.

🛠️ Tools & Skills Used
Power BI Desktop

Data Cleaning & Transformation using Power Query

DAX (Data Analysis Expressions) for calculated columns & measures

Interactive Visualizations: bar charts, line graphs, slicers, maps, and KPIs

Star Schema Modeling for efficient data relationships

📈 DAX Highlights
Some important DAX measures used:

DAX
Copy
Edit
Total Sales = SUM(Sales[Sales])
Total Profit = SUM(Sales[Profit])
Profit Margin = DIVIDE([Total Profit], [Total Sales])
Sales YoY Growth = 
    CALCULATE([Total Sales], DATEADD(Calendar[Date], -1, YEAR))
