# 📦 Inventory & Supply Chain Management Dashboard – Power BI Project

[![Power BI](https://img.shields.io/badge/PowerBI-Desktop-yellow?logo=microsoftpowerbi&logoColor=white)](https://powerbi.microsoft.com/)  
[![DAX](https://img.shields.io/badge/DAX-Data%20Modeling-blue)]()  
[![Power Query](https://img.shields.io/badge/PowerQuery-ETL-green)]()  

## Project Overview
This Power BI project involves designing and developing a fully interactive **Inventory & Supply Chain Management Dashboard** to analyze key metrics such as stock levels, warehouse utilization, lead times, and order fulfillment. The dashboard simulates real-world logistics operations and delivers actionable business insights.

The project covered the full pipeline from raw data cleaning and transformation to advanced DAX calculations and professional dashboard design.

---

## 🛠 Data Understanding
The dataset contained transaction-level records with the following fields:  
- Date, Region, Category, Supplier  
- Units Sold, Inventory Level, Warehouse Capacity  
- Transportation Cost, Order Status, Lead Time  
- Order Accuracy, COGS, Backorder Status  

The data allowed tracking both performance metrics and supply chain bottlenecks.

---

## 🔹 Data Cleaning & Preparation
Using Power Query in Power BI:  
- Fixed formatting issues, especially in the Date column  
- Removed duplicates and nulls  
- Converted data types for smooth aggregations (numbers, Booleans)  
- Created calculated columns, e.g., **Inventory Days** based on turnover  
- Built a data model with dimension tables for Region, Category, Supplier, and Warehouse  

---

## 🔹 Data Modeling & DAX Calculations
The model was structured in a **star schema** to improve relationships, performance, and filtering.  
Key DAX measures created:  
- **Inventory Turnover Ratio:** Units Sold / Avg Inventory  
- **Inventory Days:** 365 / Turnover Ratio  
- **Warehouse Utilization:** % of total warehouse capacity used  
- **Average Lead Time by Category**  
- **Units Sold by Year** (Time Intelligence)  
- **Transportation Costs by Region & Category**  
- **Order Fulfillment Metrics:** Fulfilled, Pending, and Canceled counts  

---

## 📊 Dashboard Design
- **KPI Cards:** Inventory Days, Turnover, Warehouse Utilization  
- **Bar Charts:** Transportation Costs and Inventory Levels by Region/Category  
- **Donut Chart:** Average Lead Time across categories  
- **Line Chart:** Units Sold over time  
- **Order Status Visual:** Monitor fulfillment performance  
- **Slicers:** Region and Product Category for dynamic analysis  

Colors were muted (greens, neutrals) for a supply chain/logistics theme and accessibility.

---

## 💡 Key Insights
- Warehouse Utilization was only **34%**, indicating underused capacity  
- Inventory Days averaged **15.56**, showing healthy stock movement  
- Electronics and Furniture had the highest transportation costs in the West region  
- Accessories had the highest lead time (**26+ days**), suggesting supplier inefficiency  
- Backorders: 838 fulfilled, 248 pending—highlighting a process gap  
- Units sold increased from **1K in 2021 to 198K in 2024**, indicating rapid growth  

---

## 🛠 Tools & Skills Used
- Power BI Desktop  
- Power Query (ETL)  
- DAX (Advanced Metrics)  
- Data Modeling (Star Schema)  
- Dashboard Design  
- Supply Chain & Inventory Domain Knowledge  

---

## ✅ Outcomes & Learning
- Transformed raw business data into actionable visual insights  
- Built optimized DAX measures for real-time reporting  
- Designed a professional dashboard to support decision-making  
- Gained practical experience in supply chain analytics and operational efficiency analysis  

---

## Author
**Praneeth Kumar Reddy**  
Data Analyst | Miami, FL  
[LinkedIn](https://www.linkedin.com/in/praneethreddy) | praneethkumarreddy952@gmail.com
