# 🚀 Startup Funding Analysis (2015-2020) | Power BI

**Live Dashboard:** [Insert NovyPro link here if you create one, otherwise delete this line]

## 📌 Project Overview
This is my first data analytics portfolio project. The goal of this project is to analyze the startup funding landscape from 2015 to 2020. This interactive Power BI dashboard provides a high-level overview for investors and stakeholders to quickly identify funding trends, top-performing industries, and key geographic hubs.

![Dashboard Screenshot](Insert the image file name here, e.g., dashboard.png)

## 📊 Key Insights & Findings
Based on the dataset, here are the primary takeaways:
* **Total Market Volume:** Between 2015 and 2020, 3,044 startups received a total of $38.07bn in funding.
* **Geographic Hubs:** Bangalore is the undisputed leader in startup funding, securing $18.52bn, followed by Mumbai ($4.94bn) and Gurugram ($3.87bn).
* **Top Industries:** The E-Commerce sector attracted the most investment at $8.26bn, closely followed by Consumer Internet at $6.25bn.
* **Top Funded Startups:** Flipkart led the pack with $4.76bn in total funding.
* **Investment Vehicles:** Private Equity is the dominant investment type, accounting for $27.15bn of the total funding.

## 🛠️ Technical Skills & Data Cleaning (Power Query)
As a data analyst, I know that visualizations are only as good as the underlying data. Before building the dashboard, I used **Power Query** to extensively clean and standardize the dataset:
* **Entity Standardization:** Merged duplicate records caused by data entry variations (e.g., consolidating "Flipkart" and "Flipkart.com" into a single entity to accurately report total funding).
* **Geographic Filtering:** Cleaned the location data to ensure accurate regional reporting by removing inconsistent international entries from the primary dataset.
* **Custom Formatting:** Applied custom format strings within Power BI to standardize financial values into billions (e.g., "$38.07bn") for clear, executive-level readability.
* **Data Visualization:** Built dynamic KPI cards, line charts for time-series trend analysis, and standardized bar charts with clear data labels for scannability.

## 📂 Repository Contents
* `Startup_Funding_Dashboard.pbix` - The interactive Power BI file.
* `dataset.csv` - The raw data used for this analysis.
* `README.md` - Project documentation and insights.

## 💡 What I Learned
Through this project, I developed a strong foundational understanding of the ETL (Extract, Transform, Load) process within Power BI, specifically utilizing Power Query for text standardization and data modeling.
