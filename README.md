# Sales Dashboard - Power BI

## Project Overview
An interactive Sales Dashboard built in Power BI to analyze 2019 sales 
performance across products, cities, and time periods - enabling 
data-driven decisions for sales and management teams.

## Tools & Technologies
- **Visualization:** Power BI Desktop
- **Data Transformation:** Power Query
- **Calculations:** DAX Measures
- **Data Source:** Sales Data CSV (185,000+ records)

## Dataset
| Column | Description |
|--------|-------------|
| Order ID | Unique order identifier |
| Product | Product name |
| Quantity Ordered | Number of units ordered |
| Price Each | Unit price |
| Order Date | Date and time of order |
| Purchase Address | Customer address |
| City | City of purchase |
| Sales | Total sales amount |
| Month | Month of order |
| Hour | Hour of order placement |

## Dashboard Features
- **KPI Cards** - Total Sales (4.13M), Sales Quantity (4K), Profit Margin
- **Sales by Month** - Line chart showing monthly sales trends
- **Top 5 Cities by Sales** - Map visual for geographic analysis
- **Top 5 Products by Sales** - Bar chart and Treemap comparison
- **Top 5 Best Selling Products** - Horizontal bar chart ranking
- **Interactive Filters** - City, Product, Month, and Day slicers

## Key Insights
- Highest sales recorded in December
- iPhone, Google Phone and Macbook Pro are top revenue products
- AAA Batteries and AA Batteries are top selling by quantity
- New York City and San Francisco are top performing cities

## Key DAX & Power Query Concepts Used
- SUM and COUNT aggregations
- Profit Margin calculations
- Data cleaning and transformation using Power Query
- Dynamic filtering with slicers

## Project Structure
| File | Description |
|------|-------------|
| Sales_Dashboard.pbix | Power BI dashboard file |
| Sales_Data.csv | Raw sales dataset (185K+ rows) |
| Screenshots/ | Dashboard preview images |

## Dashboard Preview
![Sales Dashboard](screenshots/dashboard_main.png)
