# Project Overview

This project analyzes user behavior and sales performance using a transactional dataset modeled as an e-commerce platform.
The dataset includes users, transactions, products, and companies, allowing the exploration of key business metrics such as revenue, average ticket, geographic distribution, and product performance.
Although the product names are inspired by a fictional universe (e.g., Game of Thrones), they are treated as generic items within a product catalog.

### Objectives
- Evaluate total sales performance against business targets
- Analyze user purchasing behavior (average spend, segmentation)
- Identify top-performing products
- Understand geographic distribution of users and sales
- Explore patterns across time (monthly and yearly trends)

### Tools & Technologies
- Power BI (data modeling & visualization)
- DAX (measures and KPIs)
- SQL (data preparation and schema design)

### Key Insights
- Sales remain stable and close to the yearly target
- Average transaction value is aligned with business goals
- A clear segment of high-value users can be identified
- Top-selling products show similar performance, with no single dominant item
- Sales activity is concentrated in a limited number of countries


### Dataset Structure
The data follows a star schema model:
Fact table: transactions
Dimensions: users, products, companies, credit cards
