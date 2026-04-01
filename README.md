# Data Warehouse Analytics Project (SQL)

## 📌 Project Overview
This project demonstrates the end-to-end process of building a Data Warehouse (Gold Layer) in SQL Server. It includes schema design, data loading via Bulk Insert, data exploration, and advanced business analytics.

## 🚀 Features
- **Schema Design:** Structured 'Gold' schema for clean, reporting-ready data.
- **Advanced Analytics:** Includes Ranking, Change-over-Time, and Cumulative Analysis.
- **Customer Segmentation:** VIP/Regular/New segmentation logic based on spending and lifespan.
- **Business Reporting:** Automated views for Customer and Product performance metrics.

## 🛠️ SQL Techniques Used
- **CTEs & Window Functions:** For ranking and performance analysis.
- **Data Modeling:** Star Schema (Fact and Dimension tables).
- **Views:** Created `report_customers` and `report_products` for BI tool integration.

## 📂 File Structure
- `/scripts`: SQL scripts organized by execution order.
- `/datasets`: Source CSV files.

## 📈 Key Insights Example
- **VIP Segment:** Identified customers with >€5000 spend and 12-month loyalty.
- **Product Analysis:** Automated classification of High vs Low performers based on revenue.

