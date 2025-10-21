Objective

To build a data-driven sales analytics dashboard that:

Monitors total revenue, profit, quantity sold, and average discount.

Provides a clear view of sales trends over time.

Enables drill-downs and interactive filtering to explore data by region, category, and customer segment.

🧩 Data Cleaning & Transformation (Power Query)

Steps followed in Power Query Editor:

Loaded Data from Excel source.

Removed Duplicates and blank values.

Changed Data Types (Date → Date type, Sales/Profit → Decimal).

Created New Columns/Measures:

Total Sales = SUM(Sales)

Total Profit = SUM(Profit)

Average Discount = AVERAGE(Discount)

Total Quantity = SUM(Quantity)

Added Date Hierarchy for Year → Quarter → Month → Day drilldowns.

Created Relationships (if multiple tables were used).

📈 Dashboard Features
1. Key Metrics Cards

Total Sales

Total Profit

Average Discount

Total Quantity

2. Trend Analysis

Line chart showing Sales and Profit Over Time (Year → Quarter → Month).

3. Category Analysis

Bar/Column charts comparing Sales by Category and Profit by Sub-Category.

4. Regional Performance

Map visualization showing Sales by Region.

Slicers for filtering by Region, Category, and Customer Segment.

5. Customer Segment Insights

Pie/Donut chart showing Contribution by Customer Segment.

6. Interactive Filters

Filters (Slicers):

Region

Category

Customer Segment

Year

7. Drill-Down Features

Click on a year → see quarterly → monthly → daily data trends.

🧮 DAX Measures Used
Total Sales = SUM(Sales[Sales])
Total Profit = SUM(Sales[Profit])
Total Quantity = SUM(Sales[Quantity])
Average Discount = AVERAGE(Sales[Discount])
Profit Margin % = DIVIDE([Total Profit], [Total Sales]) * 100

🧭 Insights Derived

Highest sales were achieved in Q4, mainly driven by the Technology category.

West Region generated the most revenue but with a slightly lower profit margin due to discounts.

Furniture category showed consistent growth throughout the year.

Top 10 customers contributed to nearly 45% of total sales.

💡 Key Takeaways

Power BI helps translate raw sales data into actionable insights.

Interactive dashboards enhance decision-making for business leaders.

Data cleaning and DAX calculations are essential for accuracy.

🏁 Conclusion

This project demonstrates end-to-end Business Intelligence workflow — from data cleaning to visual storytelling using Power BI.
It reflects the analytical capabilities needed in Business Analyst or Data Analyst roles.




