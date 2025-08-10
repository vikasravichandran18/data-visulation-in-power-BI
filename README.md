# data-visulation-in-power-BI

*COMPANY:CODTECH IT SOLUTIONS*

*NAME:VIKAS R*

*INTERN ID:CT06DH742*

*DOMAIN:BIG DATA*

*DURATION:6 WEEKS*

*MENTOR:NEELA SANTHOSH*

📌 Project Overview
This project is an interactive sales dashboard built in Power BI Desktop.
It visualizes sales performance, shipping trends, and customer insights using a sample dataset.
The dashboard allows business users to quickly understand revenue trends, product performance, and delivery timelines.

🗂 Dataset
Source: Sample Superstore Dataset

Format: Excel/CSV

Key Columns:

Order ID – Unique identifier for each order

Order Date – Date when the order was placed

Ship Date – Date when the order was shipped

Category & Sub-Category – Product classification

Sales, Profit, Quantity – Sales metrics

Region, State, City – Location details

Ship Mode – Shipping method

🔄 Data Preparation in Power BI
Data Loading

Imported dataset from Excel/CSV into Power BI.

Data Cleaning

Removed null values and fixed data type errors.

Converted Order Date and Ship Date into Date data type.

Transformations

Created a Calendar Table for time-based analysis.

Extracted Year, Month, and Weekday from order dates.

Built Dimension Tables (Products, Customers, Dates) for a star schema.

Measures (DAX)

Total Sales = SUM(Sales)

Total Profit = SUM(Profit)

Profit Margin = DIVIDE(SUM(Profit), SUM(Sales))

📊 Visualizations
The dashboard includes:

Sales by Region – Map chart showing regional sales distribution.

Sales & Profit by Category – Clustered column chart.

Monthly Sales Trend – Line chart with year slicer.

Ship Mode Analysis – Pie chart showing shipping method share.

Top 10 Products by Sales – Bar chart ranking products.

Profit Margin by Sub-Category – Column chart.
