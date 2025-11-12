Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on Superstore sales data for multiple months.
The goal is to clean, merge, analyze, and visualize sales performance to extract business insights and support data-driven decisions.

Objectives

Combine monthly Superstore data files into one dataset
Clean and preprocess the data (handle missing, duplicates, data types)
Explore relationships between Sales, Profit, Discount, and Quantity
Identify top-performing categories, regions, and segments
Visualize trends and uncover business insights

Tools & Libraries

| Tool                     | Purpose                                         |
| ------------------------ | ----------------------------------------------- |
| **Python**               | Data analysis & visualization                   |
| **Pandas**               | Data loading, merging, cleaning, transformation |
| **NumPy**                | Numerical operations                            |
| **Matplotlib / Seaborn** | Visualizations                                  |
| **OS**                   | File handling (merging monthly CSVs)            |

The dataset consists of Superstore sales records for January, February, and March.
Each file includes columns such as:

Order_ID, Order_Date, Ship_Date, Customer_Name
Segment, Region, Category, Sub_Category
Sales, Quantity, Discount, Profit
After merging, feature engineering was performed to add:
Profit_Margin = (Profit / Sales) × 100
Ship_Delay = Ship_Date − Order_Date

Data Cleaning & Preparation

Checked and handled missing values
Removed duplicates
Converted date columns to proper datetime format
Created derived columns for deeper insights

📊 Exploratory Analysis & Visualizations

Sales by Category & Region → To identify top contributors
Profit vs. Discount → To understand discount impact
Segment Performance by Region → Market segmentation insights
Best-Selling Products → Sub-category contribution
Monthly Sales Trend → Tracking sales changes over time
Profit Margin Distribution and Shipping Delay Analysis

Key Insights

Technology and Furniture categories generate the most revenue
Copiers sub-category provides the highest profit margins
High discounts reduce profit significantly
Sales are declining each month (Jan → Mar)
West region faces longer shipping delays
Overall regional sales are balanced, though East performs slightly lower

Project Structure
Superstore-EDA/
│
├── SalesData/
│   ├── superstore_jan.csv
│   ├── superstore_feb.csv
│   └── superstore_mar.csv
│
├── Superstore_EDA.ipynb   # Jupyter notebook with full analysis
└── README.md              # Project documentation

Author

Bipin Pandey
pandebipin321@gmail.com
