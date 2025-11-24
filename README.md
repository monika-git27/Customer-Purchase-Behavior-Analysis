# Customer-Purchase-Behavior-Analysis

##  Overview
This project analyzes **3,900 retail transactions** to understand customer purchase patterns, category performance, discount behavior, and subscription trends. The goal is to provide clear insights through data cleaning, SQL analysis, and an interactive dashboard.

---

##  Dataset Summary
- **Rows:** 3,900  
- **Columns:** 18  
- Includes demographics, purchase details, discounts, previous purchases, review ratings, and shipping type.  
- Missing review ratings were imputed using median values by category.

---

##  Data Preparation
- Loaded and explored the dataset.  
- Cleaned missing values and standardized column names.  
- Created `age_group` and `purchase_frequency_days`.  
- Removed redundant columns and loaded cleaned data into PostgreSQL.

---

##  SQL Analysis
Key analyses included:  
- Revenue by gender  
- High-spending discount users  
- Top-rated products  
- Standard vs Express shipping comparison  
- Subscriber vs non-subscriber revenue  
- Discount-heavy products  
- New, Returning & Loyal customer segmentation  
- Top products per category  
- Repeat buyers’ subscription likelihood  
- Revenue by age group  

---

## Power BI Dashboard
(https://github.com/monika-git27/Customer-Purchase-Behavior-Analysis/blob/main/Dashboard.png?raw=true)
Visuals included:  
- Total customers, average purchase amount, and average rating  
- Revenue & sales by category  
- Revenue & sales by age group  
- Subscription status distribution  
- Filters: gender, category, shipping type, subscription status  

---

##  Key Insights
- Clothing generates the highest revenue.  
- Young Adults & Middle-Aged groups contribute most revenue.  
- Only 27% of customers are subscribed.  
- Subscribers spend more on average.  
- Certain products rely heavily on discounts.

---

## Recommendations
- Promote subscription benefits.  
- Introduce loyalty rewards for repeat buyers.  
- Review discount-heavy products for profitability.  
- Target high-revenue age groups with focused marketing.

