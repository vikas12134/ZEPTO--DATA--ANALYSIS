🛒 Zepto SQL Data Analysis
📘 Project Overview

This project focuses on analyzing Zepto’s product dataset using SQL to gain insights into pricing, discounts, inventory, and product availability. The goal is to perform data exploration, cleaning, and analysis to understand business trends, optimize stock management, and identify high-value products.

🎯 Objectives

Explore and clean product-level data.

Identify duplicate or missing data.

Analyze discount patterns and pricing strategies.

Evaluate out-of-stock products and their impact on sales.

Estimate revenue and weight-based product segmentation.

🗂️ Dataset Description

The dataset (table: zepto) contains product-level details such as:

Column Name	Description
sku_id	Unique product identifier
category	Product category (e.g., Snacks, Beverages)
name	Product name
mrp	Maximum retail price (₹)
discountPercent	Discount percentage applied
availableQuantity	Quantity available in stock
discountedSellingPrice	Selling price after discount
weightInGms	Product weight in grams
outOfStock	Boolean flag for stock availability
quantity	Number of units ordered or listed
🧹 Data Exploration & Cleaning Steps

Count total rows and inspect sample data.

Check for null or missing values.

Identify duplicate product names.

Remove products with invalid prices (mrp = 0).

Convert prices from paise to rupees for consistency.

📊 Analytical Queries

Top 10 best-value products – Based on highest discount percentages.

High MRP but out-of-stock products – Identifies costly but unavailable items.

Estimated revenue by category – Calculates potential revenue using available quantity.

Products with low discounts and high MRP – Highlights premium items.

Top 5 categories by average discount – Shows categories offering best deals.

Price per gram analysis – Determines value-for-money products.

Product weight categorization – Groups products as Low, Medium, or Bulk.

Total inventory weight by category – Measures stock volume across categories.

🧠 Key Insights

Some products are listed multiple times, requiring data normalization.

Several products had missing or zero MRP values before cleaning.

Categories with higher average discounts tend to move inventory faster.

Out-of-stock items with high MRP indicate potential supply chain or demand forecasting issues.

⚙️ Tools & Technologies

SQL (PostgreSQL / MySQL compatible)

Database Tools: pgAdmin, MySQL Workbench, or DBeaver

Data Visualization (optional): Power BI, Tableau, or Python (Matplotlib, Seaborn)

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/yourusername/Zepto_SQL_Data_Analysis.git


Open the SQL script in your preferred SQL IDE.

Create and connect to a database.

Run the script:

\i Zepto_SQL_data_analysis.sql


Review query outputs and visualizations for insights.

📈 Conclusion

This SQL-based analysis provides actionable insights into pricing efficiency, stock management, and sales optimization for Zepto. By identifying trends in discounts, product demand, and revenue potential, businesses can make smarter decisions to enhance profitability and customer satisfaction.


✍️ Author

Name: D.SAI VIKAS
Project Title: Zepto SQL Data Analysis
Institution: MALLAREDDY UNIVERSITY
Email: VIKASSAI502@gmail.com
Github: https://github.com/vikas12134
