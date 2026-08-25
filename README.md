# E-Commerce Delivery App Sales Analysis

## 📌 Project Overview

This project focuses on analyzing e-commerce and delivery app order data to understand sales performance, customer behavior, delivery performance, customer satisfaction, and refund patterns.

The analysis was performed using Python in Google Colab with a dataset containing approximately 100,000 order records.

The main goal of this project is to convert raw transaction data into meaningful business insights that can help improve sales, delivery operations, and customer experience.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze overall sales performance
- Compare different delivery platforms
- Identify the best-performing product categories
- Analyze customer purchasing behavior
- Calculate Average Order Value (AOV)
- Analyze delivery time and delivery delays
- Study customer ratings and feedback
- Analyze refund requests
- Identify monthly and daily sales trends
- Find peak ordering hours
- Understand relationships between delivery performance and customer ratings
- Generate business recommendations based on the analysis

---

## 📊 Dataset

The dataset contains approximately 100,000 order records and 11 columns.

### Dataset Columns

| Column | Description |
|---|---|
| Order ID | Unique ID of each order |
| Customer ID | Unique ID of each customer |
| Platform | Delivery platform used for the order |
| Order Date & Time | Date and time when the order was placed |
| Delivery Time (Minutes) | Time taken to deliver the order |
| Product Category | Category of the ordered product |
| Order Value (INR) | Total value of the order in Indian Rupees |
| Customer Feedback | Feedback provided by the customer |
| Service Rating | Customer rating for the service |
| Delivery Delay | Indicates whether the order was delayed |
| Refund Requested | Indicates whether a refund was requested |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Google Colab
- Jupyter Notebook

---

## 🔄 Project Workflow

The project follows the following data analytics workflow:

1. Load the dataset
2. Understand the dataset structure
3. Check data types
4. Check missing values
5. Check duplicate records
6. Clean and prepare the data
7. Convert date and time columns
8. Create new time-based features
9. Perform Exploratory Data Analysis (EDA)
10. Analyze sales and orders
11. Analyze platforms
12. Analyze product categories
13. Analyze customers
14. Analyze delivery performance
15. Analyze ratings and feedback
16. Analyze refund requests
17. Perform correlation analysis
18. Create visualizations
19. Generate business insights
20. Provide recommendations

---

## 🧹 Data Cleaning

The following data-cleaning steps were performed:

- Checked the dataset dimensions
- Checked column names and data types
- Checked missing values
- Checked duplicate records
- Removed duplicate records where required
- Converted the `Order Date & Time` column into datetime format
- Checked invalid date values
- Created additional date and time features

### Created Features

The following features were extracted from the order date:

- Year
- Month
- Month Name
- Day
- Day Name
- Hour

These features were used for time-based sales analysis.

---

## 📈 Key Analysis

### 1. Sales Analysis

The following metrics were calculated:

- Total Orders
- Total Customers
- Total Sales
- Average Order Value
- Median Order Value

### 2. Platform Analysis

Platforms were compared using:

- Total Orders
- Total Sales
- Average Order Value
- Average Rating
- Average Delivery Time

### 3. Product Category Analysis

Product categories were analyzed based on:

- Number of Orders
- Total Sales
- Average Order Value
- Average Rating
- Average Delivery Time

### 4. Customer Analysis

Customer-level analysis was performed to identify:

- Number of orders per customer
- Total customer spending
- Average customer order value
- High-value customers

### 5. Delivery Analysis

Delivery performance was analyzed using:

- Average delivery time
- Delivery time distribution
- Delivery delay percentage
- Platform-wise delivery performance

### 6. Customer Satisfaction

Customer satisfaction was analyzed using:

- Service ratings
- Customer feedback
- Platform-wise average rating
- Delivery delay versus rating

### 7. Refund Analysis

Refund behavior was analyzed using:

- Total refund requests
- Refund request percentage
- Platform-wise refund rate
- Delivery delay versus refund requests

### 8. Time-Based Analysis

Sales trends were analyzed by:

- Month
- Date
- Day of week
- Hour of day

This helped identify high-demand periods and peak ordering hours.

---

## 📊 Visualizations

The project includes visualizations such as:

- Sales by Platform
- Orders by Platform
- Sales by Product Category
- Average Delivery Time by Platform
- Delivery Delay Distribution
- Service Rating Distribution
- Customer Feedback Distribution
- Refund Request Distribution
- Monthly Sales Trend
- Daily Sales Trend
- Sales by Hour
- Order Value Distribution
- Delivery Time Distribution
- Delivery Time vs Service Rating
- Correlation Heatmap
- Platform vs Product Category Heatmap

---

## 🔍 Business Questions

This project answers important business questions such as:

### Sales

- Which platform generates the highest sales?
- Which product category generates the highest revenue?
- What is the Average Order Value?
- Which periods have the highest sales?

### Customers

- Who are the highest-spending customers?
- How frequently do customers place orders?
- Which customers contribute the most revenue?

### Delivery

- Which platform has the fastest delivery?
- What percentage of orders are delayed?
- Does delivery delay relate to customer ratings?

### Customer Experience

- Which platform has the highest average rating?
- What type of customer feedback is most common?
- Do delayed orders receive lower ratings?

### Refunds

- What percentage of orders result in refunds?
- Which platform has the highest refund rate?
- Are delayed orders associated with more refund requests?

---

## 💡 Business Insights

The analysis can help a delivery business:

- Identify high-performing platforms
- Identify high-performing product categories
- Improve delivery operations
- Reduce delivery delays
- Improve customer satisfaction
- Reduce refund requests
- Identify valuable customers
- Plan resources during peak hours
- Improve sales and marketing strategies

> **Note:** Specific numerical findings are available in the analysis notebook and generated output files.

---

## 📌 Business Recommendations

Based on the analysis, possible recommendations include:

1. Focus on high-performing platforms and product categories.
2. Investigate the main causes of delivery delays.
3. Increase delivery capacity during peak ordering hours.
4. Monitor platforms with high refund rates.
5. Improve service quality where customer ratings are low.
6. Develop loyalty strategies for high-value customers.
7. Use sales trends for inventory and resource planning.
8. Monitor delivery performance regularly.
9. Analyze customer feedback to identify service problems.
10. Use data-driven strategies for improving customer retention.

---

## 📁 Project Structure

```text
ECommerce-Delivery-Sales-Analysis/
│
├── README.md
│
├── data/
│   └── ecommerce_delivery_analytics.csv
│
├── notebooks/
│   └── ECommerce_Delivery_Sales_Analysis.ipynb
│
├── outputs/
│   ├── platform_analysis.csv
│   ├── category_analysis.csv
│   ├── top_customers.csv
│   └── final_business_summary.csv
│
├── images/
│   ├── platform_sales.png
│   ├── category_sales.png
│   ├── monthly_sales.png
│   ├── delivery_analysis.png
│   └── correlation_heatmap.png
│
└── requirements.txt
