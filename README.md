# Business Performance Dashboard

## Project Overview
Interactive 2-page business intelligence dashboard analyzing 9,994 retail 
transactions across 4 years using SQL (MySQL) and Power BI to identify 
revenue drivers, loss-making products, and regional performance.

## Tools & Technologies
- MySQL (Data storage & SQL queries)
- Power BI Desktop (Dashboard & Visualizations)
- SQL (Data Analysis)

## Dashboard Pages

### Page 1 — Executive Overview
- Total Sales: $2.30M
- Total Profit: $286.40K  
- Total Orders: 5,009
- Total Customers: 793
- Sales trend over time
- Sales by Category (Technology, Furniture, Office Supplies)

### Page 2 — Deep Dive Analysis
- Profit by Region (West leads at 37.86%)
- Sales by Region comparison
- Profit by Sub-Category (identified loss-makers)
- Sales by Customer Segment

## Key Business Findings

### 🔴 Critical Finding — Tables Are Losing Money
Tables generate $206,965 in sales but lose $17,725 in profit (-8.56% margin).
The business is losing money on every table sold.

### 🟢 Top Performers
- Copiers: Highest profit sub-category
- West Region: Drives 37.86% of total profit
- Technology: Highest revenue category at $836K+

### 👥 Customer Insights
- Consumer segment = 50.56% of total revenue
- Corporate segment = 30.74%
- Home Office = 18.7%

## Business Recommendations
1. **Immediately review Tables pricing** — currently loss-making despite 
   high sales volume
2. **Invest more in West region** — highest profit margin performance
3. **Focus on Copiers & Phones** — highest profit sub-categories
4. **Protect Consumer segment** — drives majority of revenue

## SQL Queries Used
Key analyses performed in MySQL:
- Total revenue and profit overview
- Sales and profit by Region
- Sales and profit by Category
- Top and bottom Sub-Categories by profit
- Monthly sales trend analysis

## Project Structure
business-performance-dashboard/
├── Superstore-Business-Dashboard.pbix    ← Power BI file
├── data/
│   └── Sample - Superstore.csv          ← Dataset
└── outputs/
├── dashboard-page1.png              ← Executive Overview
└── dashboard-page2.png             ← Deep Dive Analysis
## Dataset
Sample Superstore Dataset — Kaggle
9,994 transactions | 2014–2017 | US Retail Store
