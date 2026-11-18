# TYRQUEN | Sales Analytics Dashboard

A two-page interactive Power BI dashboard designed to analyse sales performance, revenue trends, customer behaviour and product profitability.

## Project Overview

The TYRQUEN Sales Analytics Dashboard demonstrates how business data can be transformed into meaningful insights using Microsoft Power BI.

The report provides an overview of sales performance and a detailed analysis of customers, products, regions and sales channels.

**Note:** This project uses synthetic sample sales data for demonstration and portfolio purposes. It does not contain real client or business transactions.

## Dashboard Pages

### 1. Sales Performance
- Total Revenue
- Total Profit
- Total Orders
- Units Sold
- Profit Margin
- Monthly Revenue Trends
- Sales Channel Analysis
- Revenue by Region
- Product Profitability
- Key Business Observations

### 2. Detailed Sales Analysis
- Total Customers
- Average Order Value
- Salesperson Performance
- Category-wise Revenue Distribution
- Monthly Active Customers
- Top 10 Customers by Revenue
- Quarterly Revenue Trends
- Top 10 Products by Revenue
- Order-Level Discount vs Profit Analysis
- Profit Contribution by Category
- Detailed Sales Matrix

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel
- Git & GitHub

## Key DAX Measures

```dax
Total Revenue = SUM('Sales Data'[Revenue (INR)])

Total Profit = SUM('Sales Data'[Profit (INR)])

Total Orders = DISTINCTCOUNT('Sales Data'[Order ID])

Units Sold = SUM('Sales Data'[Quantity])

Profit Margin = DIVIDE([Total Profit], [Total Revenue], 0)

Total Customers = DISTINCTCOUNT('Sales Data'[Customer])

Average Order Value = DIVIDE([Total Revenue], [Total Orders], 0)
```

## Key Findings

Based on the sample dataset:

- Total revenue: ₹26.22M
- Total profit: ₹3.49M
- Total orders: 600
- Profit margin: 13.31%
- Online sales contribute approximately 41.53% of total revenue.
- Laptops generate the highest product profit.
- Coimbatore and Pune lead regional revenue.

## Interactive Features

The dashboard includes interactive slicers for:

- Region
- Category
- Sales Channel
- Year

These filters allow users to explore sales performance across different business dimensions.

## Project Structure

```text
TYRQUEN-Sales-Analytics/
│
├── TYRQUEN_Sales_Dashboard.pbix
├── tyrquen_sales_dashboard_demo.xlsx
├── README.md
│
└── Screenshots/
    ├── sales-performance.png
    └── detailed-sales-analysis.png
```

## Purpose

This project was developed as a portfolio demonstration of data analysis, dashboard development, data visualization and business intelligence skills.

**Developed by TYRQUEN**

Turning Ideas Into Intelligent Solutions.