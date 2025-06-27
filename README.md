# 📈 Supplier and Seasonal Revenue Insights Dashboard (2015–2018)
This Power BI dashboard provides a comprehensive view of supplier performance, seasonal revenue patterns, and customer segmentation from the years 2015 to 2018. Designed using a robust star schema data model, this interactive tool is ideal for data-driven decision-making in supply chain strategy, seasonal marketing campaigns, and customer analytics.


# 📊 Project Summary
The Supplier and Seasonal Revenue Insights Dashboard empowers business users to:

* Identify high-performing suppliers
* Monitor seasonal revenue shifts
* Analyze customer segment profitability
* Compare year-over-year sales trends

The project aims to transform raw sales data into actionable insights that help drive better supplier engagement, campaign timing, and strategic diversification.

# 🔍 Key Insights
🏷️ Supplier Categories
* Clothing Suppliers led with over $50M in revenue.
* Packaging Suppliers followed with around $40M.
* Toy Suppliers and Novelty Goods Suppliers had smaller, niche contributions.

# 🏢 Top Performing Suppliers
* Fabrikam, Inc. dominated with 48.56% of total supplier revenue (~$53.72M).
* Litware, Inc. contributed another 36.75% (~$40.66M), highlighting a strong performance concentration.

# 🗓️ Seasonal Trends
* Spring was the most profitable season (~$33M).
* Winter and Summer maintained steady contributions.
* Fall showed underperformance, presenting an opportunity for campaign optimization.

# 🛒 Customer Segment Performance
| Customer Category | Prior Year Sales | Year-to-Date Revenue |
| ----------------- | ---------------- | -------------------- |
| Novelty Shop      | \$56.27M         | \$8.45M              |
| Supermarket       | \$6.38M          | \$1.00M              |
| Computer Store    | \$5.12M          | \$0.94M              |
| Corporate         | \$5.10M          | \$0.75M              |
| Gift Store        | \$5.09M          | \$0.82M              |

* Novelty Shops emerged as the top contributors.
* Gift Stores and Corporate Clients showed potential for revenue improvement.

# 🧠 Data Model Overview
The dashboard is structured using a star schema, with the Fact_Revenue table at the center, connected to the following dimension tables:

* Dimensional_Supplier_Category
* Dimensional_Supplier_Name
* Dimensional_Customer_Category
* Dimensional_Date (Season, DateKey)
* Dimensional_Color (for visual segmentation)

This structure enables efficient slicing by time, supplier attributes, customer types, and visual cues.

# 🛠️ Tools & Technologies
* Power BI Desktop – For data modeling, relationships, DAX, and interactive visuals
* Excel/CSV – For raw data inputs (2015–2018)
* DAX – To compute YoY Sales, Seasonal Contributions, and Filtering Metrics
* Star Schema Design – For optimal data organization and performance

# 💡 Business Value
This dashboard helps organizations:

* Align with top-performing suppliers
* Optimize seasonal marketing campaigns
* Identify underperforming segments for targeted action
* Diversify revenue streams to mitigate supplier risks

  ![image](https://github.com/user-attachments/assets/6a0dbf9b-2334-4ebf-8b8d-b1b1df9e83a7)

# 🚀 Getting Started
* Download and open the .pbix file using Power BI Desktop.
* Explore the dashboard using filters (year, city, category).
* Modify or update data sources as needed for new timeframes or suppliers.

# ⭐ If You Found This Useful
- Leave a ⭐ on the repository and share it with your peers who work in data analytics, BI, or supply chain!










