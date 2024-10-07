# Sales-Performace-Analysis & Customer Analysis

Here’s a concise version of your approach for a GitHub README file:

# **Sales Performance Analysis with Power BI**

This project analyzes sales data using Power BI, focusing on sales trends, target achievement, what-if discount scenarios, and Pareto analysis. Data transformation and cleaning were performed in Power Query to ensure accurate reporting.

## **Data Transformation & Cleaning:**
- Imported datasets: Sales, Returns, Targets, Products, Customers, Regions, Salespersons.
- Addressed missing/inconsistent data and standardized formats.
- Joined datasets using key columns.
- Created new columns using Power Query:
  - **Net Sales** = Sales – Returns
  - **% Target Achieved** = (Net Sales / Target Sales) * 100
  - **Profit Margin** = (Profit / Net Sales) * 100
  - **What-If Discount** = Allows user input for discount % to predict profit.
    
## **Key KPIs:**
- **Total Sales**: Net Sales
- **% Target Achieved**
- **Profit Margin**

## **Power BI Dashboard Views:**
1. **Sales Performance:**
   - Displays 4-year sales trends with year-over-year comparisons by segments, categories, and regions.
2. **Target/Benchmark Analysis:**
   - Highlights regions/states that have achieved or missed current year sales targets.
3. **What-If Analysis:**
   - Allows users to input discount percentages for segments and predict profits.
4. **Pareto Analysis:**
   - Helps users check the contribution of top customers to total sales.

This project provides a detailed view of sales performance with actionable insights on targets, trends, and customer contributions.


![image](https://github.com/user-attachments/assets/1f9a549b-612a-4e76-9661-8cd54cf4b34c)

![image](https://github.com/user-attachments/assets/6dd9b80e-3e7c-46a4-b969-a638053c2458)

# Customer Analysis Using RFM

The RFM (Recency, Frequency, Monetary) analysis is employed to segment customers based on their buying behavior, providing valuable insights into their contribution to overall sales. This project showcases how Power BI can be leveraged to deliver actionable insights into both sales performance and customer behavior.

## RFM Segmentation

- **Recency**: Measures the total sales amount in the last 180 days.
- **Frequency**: Tracks the number of purchases made by a customer.
- **Monetary Value**: Represents the total sales value contributed by each customer.

Customers are classified into **low**, **medium**, and **high-value** categories, and dashboard visuals highlight each segment’s contribution to total sales.

### Bonus: Scoring Metric System
A scoring metric system has been developed to identify potential customers for targeted marketing and customer retention efforts.

## Additional Insights

### New Customers in 2021
This analysis reveals:
- The number of new customers acquired in 2021
- Their total sales amount
- Quantity purchased
- Discounts offered to them

### Top Performing Salespersons
This section lists the top 5 performing salespersons for each segment at both state and city levels. Visuals include:
- Total sales
- Average discount percentage provided by each salesperson

## Project Highlights
This project utilizes advanced techniques like:
- RFM analysis
- Pareto analysis
- What-If analysis

These methods are used in conjunction with data modeling and Power Query to deliver a comprehensive and interactive reporting experience.

## Technologies Used
- Power BI
- DAX
- Power Query
- Data Modeling

![image](https://github.com/user-attachments/assets/e9fc1aa0-a620-421a-8775-c5fe8088ef74)

![image](https://github.com/user-attachments/assets/1a3b7a1a-eb8c-49f5-b87d-5a108ee967e0)

![image](https://github.com/user-attachments/assets/d0a7f2f5-ae78-4e22-9c28-670087134f88)



