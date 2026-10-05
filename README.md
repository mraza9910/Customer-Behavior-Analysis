# Customer Shopping Behavior Analysis

## Project Overview

This project analyzes customer shopping behavior using 3,900 retail purchase records to identify patterns in customer spending, product preferences, subscription behavior, discounts, and customer loyalty.

I developed an end-to-end analytics workflow using **Python, PostgreSQL, SQL, and Power BI**, transforming raw customer data into an interactive dashboard and actionable business recommendations.

### Tech Stack

- Python (Pandas)
- PostgreSQL
- SQL
- Power BI
- Jupyter Notebook

---

## Business Problem

A retail company wants to better understand its customers' purchasing behavior in order to improve sales, customer engagement, and long-term loyalty.

The analysis focuses on questions such as:

- Which customer segments generate the most revenue?
- Do subscribers spend more than non-subscribers?
- Which products and categories perform best?
- How dependent are different products on discounts?
- Which customers demonstrate strong repeat-purchase behavior?
- How does purchasing behavior vary across demographic groups?

---

## Analytics Pipeline

Raw Data → Python → PostgreSQL → SQL Analysis → Power BI → Business Insights

### 1. Data Preparation — Python

Python and Pandas were used to:

- Explore the raw dataset
- Identify and handle missing values
- Standardize column names
- Engineer customer age groups
- Create purchase-frequency features
- Identify redundant variables
- Prepare the cleaned dataset for PostgreSQL

### 2. Database & Analysis — PostgreSQL / SQL

The cleaned data was loaded into PostgreSQL and analyzed using SQL.

Techniques used include:

- Aggregations
- Subqueries
- CASE statements
- Common Table Expressions (CTEs)
- Window functions
- Customer segmentation

The analysis addressed ten business questions covering revenue, discounts, product performance, shipping behavior, subscriptions, customer loyalty, and demographics.

### 3. Visualization — Power BI

An interactive Power BI dashboard was developed to communicate the results.

The dashboard includes:

- Total Customers
- Average Purchase Amount
- Average Review Rating
- Subscription Rate
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Interactive filters for Gender, Subscription Status, Category, and Shipping Type

## Dashboard

👉 **[View Interactive Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZTkyMjBmZmItNGQ4Yi00YWMxLWEyZTEtZTAwYWNkY2MxY2U1IiwidCI6ImZiYmY2YzYwLTAzNDQtNGMyOS05NDU5LTcyNTY4NTczOWIxOSIsImMiOjN9)**

---

## Key Insights

- Approximately **27% of customers are subscribers**, while 73% are non-subscribers.
- Subscribers and non-subscribers have similar average purchase amounts, indicating an opportunity to strengthen the value proposition of the subscription program.
- **Clothing** generates the highest revenue and sales volume among product categories.
- **Young Adults** generate the highest revenue among the analyzed age groups.
- Express shipping customers have a slightly higher average purchase amount than Standard shipping customers.
- Several products have discount usage rates approaching 50%, suggesting potential promotional dependency.
- A substantial portion of the customer base consists of repeat and loyal customers.

---

## Business Recommendations

**Strengthen Subscription Benefits**  
Develop stronger exclusive benefits and incentives to convert repeat customers into subscribers.

**Develop Customer Loyalty Programs**  
Use purchase history to reward repeat customers and encourage continued engagement.

**Optimize Discount Strategy**  
Review products with high discount dependency to balance promotional activity with profitability.

**Prioritize High-Performing Products**  
Feature highly rated and frequently purchased products in marketing and merchandising campaigns.

**Target High-Value Customer Segments**  
Use demographic and behavioral segmentation to develop more targeted marketing strategies.

---

## Repository Structure

```text
Customer-Shopping-Behavior/
│
├── README.md
├── notebooks/
│   └── EDA.ipynb
│
├── sql/
│   └── SQL-Code.sql
│
├── powerbi/
│   └── click the link
│
├── reports/
    ├── Business-Problem.pdf
    └── Customer-Shopping-Behavior-Analysis.pdf

