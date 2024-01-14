# Sales&Orders Project Analysis
## I go through data 📊 <br />
### Based on metadata I asked effective question related to sales and orders performance 

KPIs(Total Sales,Returns,Net sales,Discounts,COGS,T.customer, T.orders,…..)<br />
To enhance Customers loyalty<br />
    • What Is the Most ship mode used by our customer?<br />
    • Who are our top ten customer in terms of sales?<br />
    • Also we want to know our top 10 customers in terms of order frequency?<br /><br />
To monitor our strength and weak point?<br />
    • Which of segment of clients generates the most sales by catogary?<br />
    • Which city has the most sales Value?<br />
    • Which state has the most sales value percentage by region?<br /><br />
Performance Measurement<br />
    • What are the top performing of Product categories in term of sales and profit?<br />
    • What the Most portable product that we sell?<br /><br />
Customers experience<br />
     • On average how long it takes the orders to reach our clients Based on each shipping mode?<br /><br />

Orders performance <br />

What is the distribution of orders over time?<br />
How many orders were placed in each region or country?<br />
What is Total order value?<br />
What are the top-selling categories or sub-categories based on the number of orders?<br />
Which customer segment generates the highest number of orders?<br />
How does the order volume vary across different shipping modes?<br />
What is the average delivery duration for orders?<br />
How many orders received a discount, and what was the average discount value?<br />
Top 5 city by orders?<br />
Top 5 state by orders<br />
Top Customer based on order and his sales , orders and items<br />
Top category based on order and his sales , orders and items<br /><br /><br />

### (Data processing)
Load Datasets to power query for transformation.<br />
Orders Table:<br />
 ◦ Change data type for columns <br />
 ◦ Ship data column have multiple error ,I solve all error in this column by(splitting,add and merge conditions column,...)<br />
 ◦ Added custom column for Discount Value (Discount *Sales)<br />
 ◦ Added custom column for COGS <br />
People &Return Tables:<br />
 ◦ Make the first row as header <br />
Then<br />
Load shipping cost dataset to power query as shipping cost Table <br />

### Load and apply transformation data to excel
### Load Tables to power pivot 
 ◦ Created Measure <br />
 ◦ Make relationships between fact table (Order) and dimension tables (People,Return,shipping cost) as stat schema <br />
Created new multiple sheets for analysis and design Dashboards <br />
 ◦ Analysis sheet for answer the first question section <br />
 ◦ Dashboard creation for plane steps to design dashboard <br />
 ◦ Wireframe sheet for dashboard <br />
 ◦ Sales Dashboard calculation sheet for Sales Dashboard <br />
 ◦ Order Dashboard calculation sheet for Orders Dashboard <br />

### Design a tow Dashboard for Sales and Orders to Answer questions and Monitor the company performance
### project lifecycle
1-Understanding metadata and business needs<br />
2-Data transformation<br />
3-Visual representation<br />
4-Dashboard design<br /><br />

![Sales Dashboard](https://github.com/mostafaEltib/Sales-Dashboard/assets/108897691/4e7d964f-47d8-48b7-9cb3-6f31c0222288)
![Orders Dashboard](https://github.com/mostafaEltib/Sales-Dashboard/assets/108897691/7fa6f6cc-558b-440c-86be-f1a785824c26)

