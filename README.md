# Shopping Behaviour Analysis

## Project Overview
This project analyzes customer shopping behavior to identify patterns in spending, product preferences, and customer segments. By transforming raw transaction data into actionable insights, this analysis supports data-driven marketing strategies and business decision-making.

## Dataset Used
- <a href = "https://github.com/yvvonelle/Data-Analysis-Dashboard/blob/main/shopping_behaviour_raw_data.csv"> Raw Dataset </a>

## Dataset Description
The dataset contains comprehensive customer and transaction details, including:
* **Demographics:** Age, Gender, Location.
* **Purchase Details:** Item Purchased, Category, Size, Color, Season.
* **Financial Data:** Purchase Amount (USD), Discounts Applied.
* **Behavior Metrics:** Previous Purchases, Frequency of Purchase, Review Rating.
* **Engineered Segments:** Age Bracket, Spending Tier, Frequency Tier.

## Data Cleaning & Preparation
To ensure data integrity and ease of analysis, the following steps were taken:
1.  **Standardization:** Renamed headers using `underscores` and standardized text values for sizes and categories.
2.  **Feature Engineering:** * Created `Age_Bracket` groups (e.g., 18-25, 26-35, etc.).
    * Developed `Spending_Tier` based on purchase amount ranges.
    * Defined `Frequency_Tier` based on purchasing behavior.
3.  **Data Quality:** Formatted numeric fields and removed inconsistencies in category names.
   - <a href = "https://github.com/yvvonelle/Data-Analysis-Dashboard/blob/main/shopping_behaviour_cleaned_data.csv"> Cleaned Dataset </a>

## Key Business Questions (KPIs)
The analysis seeks to answer the following:
* How does customer spending vary by **season**?
* Which **clothing sizes** generate the highest total revenue?
* Which **product categories** contribute most to overall sales?
* How does **spending level** differ across age groups?
* Which **age group** represents the largest portion of customers?

## Dashboard & Visualizations
The final Excel dashboard provides visual insights into:
* **Seasonal Trends:** Total spend per season.
* **Inventory Insights:** Revenue distribution by size and category.
* **Demographic Analysis:** Customer count and average purchase amount by age bracket.
* **Segment Distribution:** Spending tier breakdown across different age groups.

 - <a href = "https://github.com/yvvonelle/Data-Analysis-Dashboard/blob/main/shopping%20dashboard.png"> Dashoard</a>
- <img width="1072" height="430" alt="shopping dashboard" src="https://github.com/user-attachments/assets/1677f5d7-6b0c-480d-97be-527592288559" />


## Tools Used
* **Microsoft Excel:** Data cleaning, Pivot Tables, and Dashboard creation.
  

## Conclusion
This project demonstrates the ability to transform raw data into meaningful customer segments. It serves as a foundation for more advanced analysis using SQL or Power BI to further explore predictive customer behavior.
