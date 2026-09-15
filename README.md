# Decodelab-Project-2-Exploratory-Data-Analysis-(EDA)

## Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a cleaned e-commerce dataset to uncover **patterns, trends, distributions, and key business insights.**

Following the completion of Project 1: Data Cleaning & Preparation, the dataset was analyzed using descriptive statistics and analytical techniques to better understand customer behavior, sales performance, product performance, order trends, and operational outcomes.

The insights generated from this project formed the foundation for the SQL analysis and Power BI dashboard development completed in subsequent projects.

## 🎯 Project Objective
The primary objectives of this project were to:
- Understand the structure and characteristics of the dataset.
- Calculate descriptive statistics such as mean, median, and counts.
- Identify sales trends and purchasing patterns.
- Detect unusual values and outliers.
- Evaluate customer and product performance.
- Summarize key business findings.
- Prepare analytical insights for reporting and dashboard creation.

## 🛠 Tools Used
- Microsoft Excel
- Excel formulas & Functions
- Pivot Tables 
- Pivot Charts 
- Descriptive Statistics
- Conditional Formatting
- IQR outlier analysis
- Exploratory Data Analysis
- Data Validation
- Data Visualization Techniques

## 📁 Dataset Overview

**Dataset Description**

The dataset contains e-commerce transaction records, including customer purchases, product information, payment methods, referral sources, and order statuses.

**Dataset Structure**

- Rows: 1200
- Columns: 14

**Key Fields**

- OrderID
- Date
- CustomerID
- Product
- Quantity
- Unit_Price
- Shipping_Address
- Payment_Method
- Order_Status
- Tracking_Number
- Items_In_Cart
- Coupon_Code
- Referral_Source
- TotalPrice

## 🔍 Exploratory Data Analysis Process

**1. Data Familiarization**

The dataset was reviewed to understand:
- Available variables
- Data types
- Transaction structure
- Categorical and numerical fields

This helped determine the most appropriate analytical approach for the EDA process.

**2. Descriptive Statistics**

Basic statistical measures were calculated to summarize the dataset.

**Measures Analyzed**
- Total Orders
- Total Revenue
- Average Order Value **(Mean)**
- Median Order Value
- Average Unit Price
- Product Quantities Sold
- Average Items in Cart

**Statistics Used**
- Count
- Sum
- Mean
- Median
- Minimum Value
- Maximum Value

These metrics provided a general understanding of sales performance and customer purchasing behavior.

**3. Trend Analysis**

Sales data was analyzed to identify patterns and trends over time.

**Areas Investigated**
- Monthly Sales Trends
- Revenue Trends
- Order Volume Trends
- Product Performance Trends

The analysis highlighted periods of high and low sales activity and helped identify peak business periods.

**4. Product Performance Analysis**

Products were analyzed to determine:
- Best-selling products
- Highest revenue-generating products
- Sales volume patterns

This provided insight into product demand and profitability.

**5. Customer Behavior Analysis**

Customer purchasing behavior was evaluated using:
- Order frequency
- Average spending patterns
- Items purchased per order

This helped identify characteristics of customer purchasing habits.

**6. Payment Method Analysis**

Payment methods were analyzed to determine:
- Most popular payment method
- Distribution of payment options among customers

The results provided insights into customer payment preferences.

**7. Referral Source Analysis**

Referral channels were examined to identify:
- Most effective referral source
- Revenue contribution by referral category

This helped assess marketing channel performance.

**8. Coupon Usage Analysis**

Coupon-related fields were analyzed to determine:
- Frequency of coupon usage
- Sales generated with coupons
- Sales generated without coupons
- Impact of promotional activities on revenue

**9. Order Status Analysis**

Order statuses were analyzed to evaluate operational performance.

**Status Categories**
- Delivered
- Shipped
- Pending
- Returned
- Cancelled

Analysis focused on:
- Distribution of order statuses
- Percentage of cancelled orders
- Overall fulfillment performance

# 📈 Key Findings
## Revenue Performance
- **Total Revenue**: $1,264,761.96 

- **2023**: $552,643.24
- **2024**: $480,235.87
- **2025**: $231,882.85

**Management Insight**: Revenue declined by approximately 13.1% from 2023 to 2024.
2023 contributed about 43.7% of total revenue, making it the strongest performing year.
The lower revenue recorded in 2025 may be attributed to the fact that the dataset only covers First half of the year.

## Product Performance
- **Top Revenue Products**: Chair, Printer, Laptop
- **Lowest Revenue Products**: Phone, Desk

**Management Insight**: ✅ Chairs, Printers and Laptop generated the highest revenue. Chairs achieved the highest revenue partly due to the highest sales volume.
✅ Phones and Desk generated the lowest revenue despite being a major product category. Although sold frequently, they tend to generate smaller transaction values.

## Customer Insights
- Average order values revealed typical spending patterns.
- Customers exhibited varying purchasing behaviors.

## Marketing Insights
- Referral sources contributed significantly to revenue generation. Instagram generated the highest total revenue ($275,285.45), contributing approximately 21.8% of total sales while Facebook attracts customers who spend more per transaction with the highest Average Order Value ($1,098.29), indicating higher-value customers.
- Coupon usage also influenced purchasing behavior and sales outcomes. FREESHIP generated the highest revenue ($335,036.99) and highest Average Order Value ($1,070.41). WINTER15 was the least effective among the promotional offers. Customers may perceive shipping costs as a significant barrier to purchase.

## Operational Insights
- Approximately 1 in every 5 orders was cancelled, representing a cancellation rate of 20.83%. This is the highest among all order statuses and may indicate challenges in the purchasing or fulfillment process.
- The return rate is also significant at 20.58%, meaning nearly another fifth of all orders were returned after purchase. This could indicate product quality concerns, customer dissatisfaction, inaccurate product descriptions, or delivery-related issues.
- Only 19.25% of orders were marked as Delivered, which is lower than both the cancellation and return percentages. This suggests that a substantial proportion of potential revenue may not be fully realized.
- Nearly 20% of orders remain pending, indicating possible delays in order processing, inventory availability, or logistics operations.     

## Trend Insights
- Monthly performance trends revealed that **June** recorded the highest number of orders (147) which translated to the month with the highest revenue ($170,616.13), making it the busiest sales month. June represents the peak demand period, while **January** recorded the highest **Average Order Value** ($1,172.77).

# 📊 Visualizations Created
The following visualizations were used during the EDA process:
