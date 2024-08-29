# Leveraging-Sales-Data-for-Business-Strategy-A-Walmart-Case-Study

## Overview

This project involves a detailed analysis of Walmart's sales data, aimed at identifying high-performing branches and products, analyzing sales patterns, and understanding customer behavior. The dataset used in this project is sourced from the Kaggle Walmart Sales Forecasting Competition.

## Project Objectives

- **Product Analysis:** Gain insights into various product lines, determine top-performing products, and identify areas for improvement.
- **Sales Analysis:** Analyze sales trends and evaluate the effectiveness of sales strategies.
- **Customer Analysis:** Identify customer segments, understand purchasing trends, and evaluate profitability associated with different customer types.

## Data Description

The dataset contains sales transactions from three Walmart branches located in Mandalay, Yangon, and Naypyitaw. It includes the following columns:

| Column              | Description                         | Data Type           |
|---------------------|-------------------------------------|---------------------|
| invoice_id          | Invoice of the sales made           | VARCHAR(30)         |
| branch              | Branch at which sales were made     | VARCHAR(5)          |
| city                | The location of the branch          | VARCHAR(30)         |
| customer_type       | The type of the customer             | VARCHAR(30)         |
| gender              | Gender of the customer making purchase | VARCHAR(10)         |
| product_line        | Product line of the product sold     | VARCHAR(100)        |
| unit_price          | The price of each product            | DECIMAL(10, 2)      |
| quantity            | The amount of the product sold       | INT                 |
| VAT                 | The amount of tax on the purchase    | FLOAT(6, 4)         |
| total               | The total cost of the purchase       | DECIMAL(12, 4)     |
| date                | The date on which the purchase was made | DATETIME            |
| time                | The time at which the purchase was made | TIME                |
| payment             | The total amount paid                | DECIMAL(10, 2)      |
| cogs                | Cost Of Goods Sold                   | DECIMAL(10, 2)      |
| gross_margin_pct    | Gross margin percentage              | FLOAT(11, 9)        |
| gross_income        | Gross Income                         | DECIMAL(12, 4)     |
| rating              | Rating                               | FLOAT(2, 1)         |

## Approach

1. **Data Wrangling:**
   - Checked for and handled missing values.
   - Verified and ensured correct data types.
   - Created a database and table to insert and manage data.

2. **Feature Engineering:**
   - Added `time_of_day` to categorize sales by Morning, Afternoon, and Evening.
   - Added `day_name` to identify the day of the week for each transaction.
   - Added `month_name` to determine sales trends by month.

3. **Exploratory Data Analysis (EDA):**
   - Analyzed sales data to address various business questions and gain insights into product performance, sales trends, and customer behavior.

## Key Questions Addressed

- **Product Analysis:**
  - How many distinct product lines are there?
  - What is the most common payment method?
  - Which product line generated the highest revenue?
  - Which city has the highest revenue?

- **Sales Analysis:**
  - Number of sales made at different times of the day and days of the week.
  - Customer type with the highest revenue and VAT contributions.

- **Customer Analysis:**
  - Unique customer types and payment methods.
  - Gender distribution and ratings trends across different times and branches.

## Insights & Recommendations 

## Product Analysis

### Top-Performing Product Lines
- **Insight:** Certain product lines consistently generate higher revenue and sales volume.
- **Recommendation:** Focus on promoting top-performing product lines through targeted marketing and strategic placement. Consider expanding the range or introducing similar products to capitalize on their popularity.

### Product Line Performance by Branch
- **Insight:** Performance of product lines varies across branches.
- **Recommendation:** Customize inventory and marketing strategies for each branch based on the performance of product lines. For branches with lower sales, investigate local preferences and adjust product offerings accordingly.

### Product Line Revenue and VAT
- **Insight:** Some product lines incur higher VAT and generate more revenue.
- **Recommendation:** Review pricing strategies and explore opportunities for cost reduction or price adjustments on high VAT products. Enhance profitability by optimizing the cost structure.

## Sales Analysis

### Sales Trends by Time of Day
- **Insight:** Sales volumes peak at specific times of the day.
- **Recommendation:** Adjust staffing levels and promotional activities based on peak sales times. Implement time-based promotions or discounts to boost sales during off-peak hours.

### Monthly Revenue Trends
- **Insight:** Certain months show higher sales and revenue.
- **Recommendation:** Plan marketing campaigns and inventory stocking in advance for high-revenue months. Consider seasonal promotions or events to capitalize on increased consumer spending.

### Branch Performance
- **Insight:** Some branches outperform others in terms of sales and product movement.
- **Recommendation:** Analyze the practices and strategies of high-performing branches and replicate successful approaches across other branches. Provide additional support and resources to branches with lower performance.

## Customer Analysis

### Customer Segmentation
- **Insight:** Different customer segments have varying purchasing behaviors and profitability.
- **Recommendation:** Tailor marketing strategies and product offerings to different customer segments. Develop personalized promotions and loyalty programs to enhance customer engagement and increase repeat purchases.

### Payment Methods and VAT Contributions
- **Insight:** Certain customer types and payment methods are associated with higher VAT contributions.
- **Recommendation:** Optimize payment processing strategies and explore ways to reduce VAT impact. Implement promotions that encourage the use of specific payment methods or customer types that contribute positively to revenue.

### Customer Ratings by Time and Day
- **Insight:** Customer satisfaction ratings vary by time of day and day of the week.
- **Recommendation:** Ensure consistent service quality during all times of the day. Address any issues leading to lower ratings by focusing on customer service improvements during specific times or days.

## General Recommendations

### Enhanced Data Analytics
- **Recommendation:** Continuously monitor sales data and customer behavior to identify new trends and opportunities. Invest in advanced analytics tools and techniques to gain deeper insights.

### Operational Efficiency
- **Recommendation:** Streamline operations and inventory management based on sales patterns. Implement efficient supply chain practices to reduce costs and improve product availability.

### Customer Engagement
- **Recommendation:** Develop targeted marketing campaigns based on customer preferences and purchasing patterns. Use data-driven insights to enhance customer experiences and build brand loyalty.

### Sales Forecasting
- **Recommendation:** Utilize predictive analytics to forecast future sales trends and adjust strategies accordingly. Implement machine learning models to enhance forecasting accuracy and support strategic decision-making.

By implementing these insights and recommendations, Walmart can optimize its sales strategies, improve branch performance, and enhance overall customer satisfaction.
