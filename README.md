# FUTURE_DS_01
Power BI Sales Analytics Dashboard that analyzes total sales, profit, discounts, and customer segments to generate actionable business insights.

# 📌 Task Overview
The goal of this project was to build an interactive Sales Analysis Dashboard to analyze business performance using sales data.

# 🎯 Objective

To transform raw sales data into meaningful insights by:

*Tracking overall business performance (Sales, Profit, Quantity, Discount)
*Identifying top-performing customer segments.
*Analyzing product category and sub-category performance.
*Understanding shipping preferences.
*Studying yearly sales and profit trends.
*Comparing sales performance across cities and regions.

 # 🛠️Tools Used

Microsoft Power BI Desktop

Excel / CSV Sales Dataset (Superstore-style dataset)

DAX Measures for KPI calculation

 # 🧹 Data Preparation Steps

Loaded raw sales dataset into Power BI

Fixed incorrect data types (Sales, Profit → Decimal Number)

Cleaned date fields

Verified categorical fields (Category, Region, Segment)

Built calculated measures using DAX.

# 📐 KPI Measures Created

The following business KPIs were created using DAX:

Total Revenue = SUM('Sample - Superstore'[Sales])

Total Profit = SUM('Sample - Superstore'[Profit])

Total Orders = DISTINCTCOUNT('Sample - Superstore'[Order ID])

Total Units Sold = SUM('Sample - Superstore'[Quantity])

These KPIs are displayed as top-level dashboard cards.

# 📊 Dashboard Visuals Included

✅ KPI Cards

Total Revenue

Total Profit

Total Orders

Total Units Sold

✅ Trend Analysis

Revenue Trend Over Time (Line Chart)

✅ Product Performance

Top 10 Products by Revenue (Bar Chart with Top N filter)

✅ Category Analysis

Revenue by Category (Column Chart)

✅ Regional Analysis

Revenue by Region (Bar Chart)

✅ Profitability Insight

Sales vs Profit (Scatter Plot)

✅ Interactive Filters (Slicers)

Region

Category

Segment

Order Year

This makes the dashboard interactive and user-driven.


# 💡 Key Business Insights

A small number of products contribute a large share of total revenue (Top-10 concentration effect)

Certain categories generate high revenue but comparatively lower profit margins

Regional performance varies significantly — some regions outperform consistently

Sales and profit are positively related, but not uniformly — indicating margin differences

Revenue shows time-based fluctuation patterns useful for forecasting

# 🚀 Business Recommendations

Focus marketing and inventory on top revenue-generating products

Improve margins in high-sales but low-profit categories

Target underperforming regions with promotional strategies

Use time trend patterns for demand planning

Monitor profit vs sales scatter clusters to detect inefficient product lines

📁 Repository Contents FUTURE_DS_01.pbix → Power BI dashboard file dataset.xlsx / csv → Source dataset dashboard_screenshot.png → Dashboard preview README.md → Project documentation

🎯 Skills Demonstrated

Data cleaning & preparation

KPI design

DAX measure creation

Business trend analysis

Top-N filtering

Interactive dashboard design

Insight generation

Business storytelling with data

# 📸 Dashboard preview
(https://github.com/rashminaphade/FUTURE_DS_01/blob/main/Screenshot%202026-02-14%20143207.png)

# 📌 How to Use This Dashboard

Open the .pbix file in Power BI Desktop

Use slicers (Region, Category, Segment, Year) to filter results

Hover on visuals to see detailed metrics

Use Top-10 product chart to identify key revenue drivers

# 🔗 Internship Track Code Track:
Data Science & Analytics Code: DS Task: 01 Repository Name: FUTURE_DS_01


