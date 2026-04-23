# Cafe Sales Analysis Dashboard ☕📊

A comprehensive Power BI project focused on end-to-end data processing—from handling "dirty" Kaggle datasets to building a professional sales performance dashboard. While the visual layout was inspired by **The Data Girl**, the critical data cleaning and preprocessing stages were performed independently.

---

## 📌 Project Overview
The primary goal of this project was to transform raw, unorganized cafe transaction data into actionable business insights. The analysis tracks key performance indicators (KPIs), monthly sales trends, and customer purchasing behavior.

## 🛠️ Tech Stack
* **Tool:** Power BI Desktop
* **Data Source:** [Kaggle - Cafe Sales Dirty Data](https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training)
* **Engine:** Power Query (M Language) for ETL processes.

## 🧼 Data Cleaning (Independent Implementation)
Since the source data was "dirty," I implemented several custom cleaning steps in Power Query:
* **Mathematical Imputation:** Resolved `null` values in `Total Spent` by calculating `Quantity * Price Per Unit`.
* **Error Handling:** Fixed data type mismatches that caused a 2% error rate in numeric columns.
* **Chronological Sorting:** Created a custom `Month Number` column to override alphabetical sorting for monthly trends.
* **Data Sanitization:** Performed Trim and Clean operations to remove non-printable characters.

## 📈 Dashboard Features
* **Core KPIs:** Total Sales, Transaction Count, and Average Price per Unit.
* **Trend Analysis:** Line charts displaying monthly fluctuations in revenue and volume.
* **Segmented Insights:** Breakdown of sales by **Location** (In-store vs. Takeaway) and **Payment Method**.
* **Product Performance:** Identification of top-selling items like Salads and Sandwiches.

## 📜 Credits
* **Visual Design:** Dashboard structure inspired by [The Data Girl's Power BI Tutorial](https://youtu.be/bOLI9CmeUHY).
* **ETL & Data Cleaning:** Independently executed by **Suhash Maniam Pillai**.
