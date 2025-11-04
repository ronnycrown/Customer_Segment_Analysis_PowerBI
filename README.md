# Customer_Segment_Analysis_PowerBI.

This project involves a comprehensive analysis of a customer segment dataset to uncover key business intelligence and performance metrics. The goal was to transform raw customer data into an interactive Power BI dashboard, providing actionable insights into revenue, profitability, and customer behaviour across different segments.

## Table of Contents.
---
1. [Data Sources](data-sources)
2. [Tools and Technologies](tools-and-technologies)
3. [Key Metrics and Insights Calculated](key-metrics-and-insights-calculated)
4. [DAX Implementation](dax-implementation)
5. [Lessons Learned](lessons-learned)

### Data Sources.
---
Sales data: The primary data used for this analysis is the "Superstore.csv" from Kaggle. It contained data on customers, including the orders they placed from each region, spanning four years, from 2011 to 2014.

### Tools and Technologies.
---
- Microsoft PowerBI - For Data Modelling, DAX and Visualisation.
- DAX(Data Analysis Expressions - For creating calculated measures and columns.
- Power Query - For Data Transformation and Cleaning. 

### Key Metrics and Insights Calculated.
---
1. Revenue by Customer Segment.
2. Total Profit by Customer Segment.
3. Overall Business Health:
   - Total Revenue.
   - Total Profit.
   - Total Orders.
   - Number of Customers.
4. Performance Metrics:
   - CLV (Customer Lifetime Value).
   - AOV (Average Order Value).
   - GPM (Gross Profit Margin).
5. Growth Analysis:
   - Revenue YoY (Year Over Year) and MoM (Month Over Month) Growth.
   - Profit YoY (Year Over Year) and MoM (Month Over Month) Growth.

### DAX Implementation.
---
A significant part of this project was writing DAX formulas to create dynamic measures. This was a challenging but rewarding process. Some of the key DAX concepts used include:
- CALCULATE(): For modifying filter context (crucial for YoY/MoM calculations).
- SUM(), AVERAGE(), DISTINCTCOUNT(): Basic aggregation functions.
- Creating explicit measures for all KPIs to ensure accuracy and reusability.

### Lessons Learned.
---
- DAX is powerful, but it has a learning curve. Understanding the context row and filter is fundamental.
- Data modelling is the foundation: A clean and well-structured data model is critical for accurate DAX calculations.
- Visualisation is about storytelling: Choosing the right chart for the right metric makes insights more accessible.
