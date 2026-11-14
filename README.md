End-to-End E-Commerce Data Analytics  Project
📋 Project Overview
An e-commerce company generates thousands of customer orders, product listings, and sales transactions daily. However, raw transactional data alone does not provide clear direction for strategic decision-making.
The primary objective of this project is to transform raw e-commerce data into actionable business insights by analyzing sales, profit, customer behavior, product performance, discounts, returns, and future demand.

❓ Key Business Questions Addressed
This project is designed to answer seven core management questions:
Revenue & Profitability: How much revenue and profit did the company generate?
Product Performance: Which products and categories perform best?
Customer Value: Which customers generate the most revenue?
Discount Impact on Profit: Does offering discounts negatively or positively impact profitability?
Discount Impact on Order Value: Does discounting significantly affect the Average Order Value (AOV)?
Profit Prediction: Can we build a model to accurately predict order-level profit?
Sales Forecasting: Can we forecast future sales demand for the upcoming months?

🛠️ Technology Stack
Database Management: SQL Server
Programming & Data Manipulation: Python, Pandas, NumPy
Data Visualization: Matplotlib, Seaborn
Statistical Analysis: SciPy (Hypothesis Testing)
Machine Learning & Forecasting: Scikit-learn, Time Series Forecasting
Business Intelligence & Dashboarding: Power BI

🗄️ Database Architecture
The relational database is structured around five core tables:
Customers: Customer demographics and regional details.
Products: Product catalog, categories, cost pricing, and retail pricing.
Orders: Order-level transaction records linking customers and dates.
OrderDetails: Line-item details including quantity, unit price, discounts, and profit.
Returns: Records of returned orders for return-rate and loss analysis.

🚀 How I Built This Project (Step-by-Step Workflow)
Step 1 & 2: Database Setup & SQL Extraction
Stored and managed the raw e-commerce datasets inside SQL Server.
Wrote SQL queries to join tables (Customers, Orders, OrderDetails, Products, Returns) and extract clean views for analysis.
Step 3 & 4: Python Integration & Data Cleaning
Connected SQL Server directly to a Python environment.
Performed data cleaning using Pandas and NumPy—handling missing values, fixing data types, removing duplicates, and engineering key features (such as profit margins and order values).
Step 5: Exploratory Data Analysis (EDA)
Investigated historical trends using Matplotlib and Seaborn to understand what happened before predicting what will happen.
Analyzed monthly sales trends, category/regional performance, customer purchasing behavior, discount patterns, profit distributions, and outliers.
Step 6: Statistical Analysis
Went beyond basic EDA by calculating key descriptive statistics: Mean, Median, Mode, Variance, Standard Deviation, Quartiles, Percentiles, and Correlations to understand data distribution and spread.
Step 7: Hypothesis Testing (Business Experiment)
Conducted a statistical experiment to test whether discounts truly drive higher order values:
Null Hypothesis (H0): Discount has no significant effect on Average Order Value (AOV).
Alternative Hypothesis (H1): Discount has a significant effect on Average Order Value (AOV).
Methodology: Applied a t-test using SciPy, evaluating the resulting p-value against the chosen significance level () to accept or reject H0.
Step 8: Machine Learning (Order Profit Prediction)
Built a supervised Machine Learning regression model using Scikit-learn to predict Order Profit.
Features Used: Quantity, Unit Price, Discount, Category, Region, and Customer Information.
Model Evaluation: Evaluated model accuracy and error rates using MAE (Mean Absolute Error), RMSE (Root Mean Squared Error), and R2 Score.
Step 9: Time Series Sales Forecasting
Aggregated historical monthly sales data to analyze seasonality and long-term trends.
Built a Time Series Forecasting model to predict future sales demand over a 6-month forecast horizon.
Step 10: Power BI Executive Dashboard
Consolidated insights from SQL, Python, statistical tests, ML predictions, and sales forecasts into an interactive Power BI Dashboard.
Dashboard Pages Included:
Executive Overview: High-level KPIs (Total Revenue, Total Profit, Total Orders, Active Customers, Average Order Value).
Sales Analytics: Regional and monthly revenue/profit trends.
Product Analytics: Top-performing categories, best-selling products, and return rates.
Customer Analytics: High-value customer segmentation and purchasing behavior.
Forecasting: Visualized historical vs. 6-month projected sales.

🎯 Final Outcome
By combining SQL data engineering, Python statistical rigor, machine learning, and Power BI storytelling, this project moves beyond raw numbers to deliver actionable business insights for optimizing discount strategies, inventory planning, and customer retention.

