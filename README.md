
# E-Commerce-Retail-Data-Analysis

Creating a PowerPoint presentation specifically focused on e-commerce retail data analysis related to customer transactions and new products.

## Data Analysis Project

**OVERVIEW**

This repository contains data for a comprehensive analysis project. The dataset includes transaction information, customer details, and product category information. The purpose of this project is to analyze customer behavior, sales trends, and product performance.

**DATA SET OVERVIEW**

### 1. Transactionsnew.csv

**Columns:**
- `transaction_id`: Unique identifier for each transaction.
- `cust_id`: Customer identifier.
- `tran_date`: Date of the transaction.
- `prod_cat`: Product category.
- `prod_subcat`: Product sub-category.
- `amt`: Transaction amount.

### 2. Customers_new.csv

**Columns:**
- `cust_id`: Unique identifier for each customer.
- `cust_name`: Name of the customer.
- `DOB`: Date of birth of the customer.
- `Gender`: Gender of the customer.
- `city_code`: Code representing the city of the customer.

### 3. prod_cat_info.csv

**Columns:**
- `prod_cat_code`: Code representing the product category.
- `prod_cat`: Name of the product category.
- `prod_sub_cat_code`: Code representing the product sub-category.
- `prod_subcat`: Name of the product sub-category.


**Analysis Business Goals**

Customer Segmentation: Identify different segments of customers based on their transaction history and demographics.
Sales Analysis: Analyze sales trends over time and across different product categories.
Product Performance: Evaluate the performance of different product categories and sub-categories.


----------------------------------------------------------------------------------------

# Objectives
**Customer Segmentation**

Goal: Identify distinct groups of customers based on their purchasing behavior and demographics.
Analysis: Cluster customers using data from Transactionsnew.csv and Customers_new.csv.
Analyze purchase frequency, transaction amounts, and product categories.
Segment customers based on demographic information (age, gender, city).
 

**Sales Trend Analysis**

Goal: Understand sales trends over different periods.
Analysis: Examine transaction dates in Transactionsnew.csv to identify sales trends over time (daily, monthly, yearly).
Determine peak sales periods and seasonal patterns.
Analyze how different product categories (from prod_cat_info.csv) contribute to sales trends.


**Product Category Performance**

Goal: Evaluate the performance of various product categories and sub-categories.
Analysis: Use data from Transactionsnew.csv and prod_cat_info.csv to assess sales and profitability for each product category.
Identify best-selling and underperforming categories and sub-categories.
Analyze trends in product category performance over time.

**Customer Demographics and Behavior**

Goal: Understand how customer demographics impact purchasing behavior.
Analysis: Correlate demographic data from Customers_new.csv with transaction behavior from Transactionsnew.csv.
Identify which demographic groups have the highest and lowest spending.
Tailor marketing strategies based on demographic insights.


**Market Basket Analysis**

Goal: Discover associations between products to enhance cross-selling and upselling strategies.
Analysis: Conduct association rule mining on transaction data from Transactionsnew.csv to find frequently co-purchased products.
Use insights to create targeted marketing campaigns that promote related product

------------------------------------------------------------------------------------------------------------------------------------------------------------

# Analysis of E-commerce Retail Data

Key Insights

**1)Most Frequently Used Transaction Channel**

The predominant transaction channel used by customers is the e-Shop channel. This finding underscores the importance of optimizing strategies tailored specifically for this channel to enhance customer experience and satisfaction.

**2)Gender Distribution of Customers**

The database contains a breakdown of customers by gender, revealing insights into the number of male and female customers. This data is crucial for devising gender-specific marketing strategies and identifying demographic trends.

**3)City with Maximum Customer Base**

The city with city_code 3 hosts the largest customer base, totaling 595 individuals. This information is invaluable for planning geographical expansion and targeting localized marketing efforts.

**4)Sub-categories under the Books Category**

Within the Books category, there are 6 distinct sub-categories. This detail aids in catalog management and provides insights into product diversification within the category.

**5)Maximum Quantity of Products Ordered**

The highest quantity of products ever ordered by a customer is 5 units. Understanding such purchasing patterns informs inventory management strategies and ensures adequate stock levels.

**6)Net Total Revenue in Electronics and Books Categories**

The electronics category generated a net total revenue of 10,722,463.635, while the Books category yielded 12,822,694.04. This financial data facilitates category-specific performance analysis and strategic decision-making.

**7)Customers with >10 Transactions (Excluding Returns)**

A total of 6 customers have conducted more than 10 transactions, excluding returns. This insight is pivotal for customer retention strategies and loyalty program initiatives.

**8)Combined Revenue from Electronics & Clothing in Flagship Stores**

Flagship stores have collectively earned 3,851,454.295 in revenue from the Electronics and Clothing categories. This metric aids in evaluating flagship store performance and guiding operational improvements.

**9)Total Revenue from Male Customers in the Electronics Category**

Male customers contributed to the total revenue in the Electronics category, segmented by product sub-categories. This analysis provides gender-specific insights into purchasing behavior and category preferences.

**10)Sales and Returns Percentage by Top 5 Sub-categories**

The top 5 sub-categories based on sales data are analyzed for sales and returns percentages, enhancing profitability analysis and customer satisfaction efforts.

**11)Net Total Revenue from Customers Aged 25-35 in Last 30 Days**

Customers aged between 25 to 35 years generated a specific net total revenue in the last 30 days, offering insights into purchasing behaviors within this demographic over a defined period.

**12)Product Category with Maximum Returns in the Last 3 Months**

Home and Kitchen category experienced the highest volume of returns in the past 3 months. This insight guides quality improvement initiatives and enhances customer service strategies.

**13)Store-Type Selling Maximum Products by Sales Amount and Quantity**

The e-Shop store emerged as the leader in product sales by both quantity and sales amount. This data aids in inventory management and strategic planning for future sales initiatives.

**14)Categories Exceeding Average Revenue**

Categories such as Bags, Books, Clothing, and Electronics surpassed the overall average revenue (excluding returns), highlighting areas of strength to maximize profitability and market share.

**15)Average and Total Revenue by Subcategory in Top 5 Categories**

Detailed analysis of average and total revenue by sub-category within the top 5 categories by quantity sold offers strategic insights for product-specific marketing and sales strategies.
_____________________________________________________________________________________________________________________________________________________
# KEY RECOMMENDATION

**1. Customer Transaction Analysis:**
Increase Average Transaction Value (ATV):
Offer bundle deals or discounts for multiple purchases.
Implement upselling and cross-selling strategies during checkout.

**2. New Product Category Analysis:**
Market Research and Validation:
Conduct thorough market research to understand demand and competition.
Use focus groups or surveys to gather feedback on potential new products.

**3. Implementation Strategy**
·  Prioritize Actionable Insights:
Focus on insights that directly impact revenue, customer satisfaction, and operational efficiency.
Allocate resources to initiatives with the highest potential ROI based on data analysis.
·  Continuous Improvement:
Foster a culture of data-driven decision-making within the organization.
Regularly review and update strategies based on new data and market dynamics

-------------------------------------------------------------------------------------------------------------------------------------------------------------







