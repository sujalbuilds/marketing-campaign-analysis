# Data Analysis Project: Marketing Campaign Insights

This repository showcases a structured **Data Analysis (DA)** approach to uncover actionable insights from a marketing campaign dataset. It emphasizes exploratory techniques, statistical validation, and clear visual storytelling—no predictive modeling required.

## 🔍 Project Overview

* Perform data cleaning and validation to ensure data quality.
* Conduct Exploratory Data Analysis (EDA) to summarize key patterns.
* Apply statistical tests to confirm findings.
* Visualize results with publication-ready charts.
* Provide data-driven recommendations.

## 📊 Data Sources

* **marketing\_campaign.csv**: Single source file with the following key fields:

  * Customer identifiers and demographics: `ID`, `Year_Birth`, `Education`, `Marital_Status`, `Income`, `Kidhome`, `Teenhome`
  * Engagement & recency: `Dt_Customer` (enrollment date), `Recency` (days since last purchase)
  * Monetary metrics: `MntWines`, `MntFruits`, `MntMeatProducts`, `MntFishProducts`, `MntSweetProducts`, `MntGoldProds`
  * Purchase frequency proxies: `NumDealsPurchases`, `NumWebPurchases`, `NumCatalogPurchases`, `NumStorePurchases`, `NumWebVisitsMonth`
  * Campaign responses: `AcceptedCmp1-4`, `Response`, `Complain`

## 🛠️ Tools & Technologies Tools & Technologies & Technologies

* **Python & Jupyter Notebook** for interactive analysis.
* **pandas & NumPy** for data wrangling.
* **matplotlib** for custom visualizations (bar charts, histograms, heatmaps).
* **SciPy Stats** for statistical hypothesis testing.

## 📑 Table of Contents

1. Data Overview
2. Data Cleaning & Feature Engineering
3. Demographic Profiling
4. Spending Behavior
5. Temporal Analysis
6. RFM Segmentation
7. Response & Channel Analysis
8. Executive Insights & Recommendations

## 📰 Key Insights

* **Demographics**: Customers aged 31–45 show the highest response (\~23%).
* **Education Impact**: Postgraduates respond at a rate 10% above the overall average.
* **Channel Trends**: Email engagement peaks mid-week; social media shows rising weekend activity.
* **Statistical Significance**: χ² tests confirm significant differences (p < 0.05) in response by education level.

## ✅ Recommendations

* **Target High-Response Cohorts**: Focus messaging on the 31–45 age group and postgraduate segment.
* **Optimize Channel Timing**: Schedule email blasts mid-week and ramp up social posts around weekends.
* **Data Quality**: Implement monitoring to reduce missing values in key demographic fields.
* **Ongoing Analysis**: Refresh analyses monthly and incorporate A/B test results for continuous improvement.

## 🤝 Contributing

Contributions to extend the analysis—such as deeper segmentation, advanced visualizations, or additional statistical tests—are welcome!

