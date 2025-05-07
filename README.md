# 📊 Adventure Works Sales Analysis – Power BI Project
## 📘 Project Overview
This project is a complete end-to-end Power BI report I built using sales data from Adventure Works, a company that sells motorbike accessories and sports clothing. The goal was to help the business understand how their sales, products, customers, and regions performed between 2020 and 2022. I created an interactive dashboard that highlights key metrics and trends, making it easier for decision-makers to spot opportunities and areas that need attention.
## 📝 Project Problem Statement
The Adventure Works management team needed a comprehensive understanding of their business performance over the years 2020 to 2022, specifically in terms of sales, customer behavior, returns, and territory-level performance. However, their data was siloed and lacked meaningful visualization. This project aimed to bridge that gap by:

- Consolidating the data

- Creating relevant metrics

Designing a visual report that identifies business strengths and growth opportunities
## 🎯 Key KPIs (Key Performance Indicators)
The following KPIs were calculated and visualized using DAX (Data Analysis Expressions):

🏷 Total Sales

📦 Total Quantity Sold

💰 Total Profit

🔁 Return Rate

📈 Monthly and Quarterly Sales Trends

🔝 Top-Performing Products

🌍 Performance by Territory

👥 Top Customers by Revenue

🔄 Rolling Profit (3-month rolling total)
## 🧩 Steps Followed
1. Data Loading & Shaping

- Imported multiple datasets: Sales, Product, Customer, Returns, Category, Territory.

- Cleaned and shaped data in Power Query.

- Handled nulls, ensured date formats were consistent, and removed unnecessary columns.

2. Data Modeling

- Established relationships using star schema.

- Created a calendar table to enable time-based analysis.

- Built proper relationships between fact and dimension tables.

3. DAX Measures

- Created dynamic measures for KPIs using DAX.

- Built time-intelligent measures like YOY growth and rolling totals.

4. Dashboard Design

- Developed a multi-page interactive report with slicers and drill-downs.

- Used visual elements like bar charts, line graphs, cards, and maps.

## ❓ Key Business Questions Answered
📆 How have sales trended from 2020 to 2022?

🛍 Which product categories and products generate the most revenue and profit?

🌍 Which territories contribute most to overall sales and growth?

🔁 What is the return rate by product category?

👤 Who are the top customers by total purchase value?

📊 How does quarterly performance vary across years?

📦 Are there seasonal patterns in quantity sold?

## 📌 Tools & Technologies Used
Power BI Desktop

Power Query

DAX

Star Schema Modeling

Interactive Dashboard Design
## 🔍 Key Insights
The sales analysis revealed that North America was the highest-selling territory, followed by Australia and then Europe, making these regions critical to the company’s revenue stream. Between 2020 and 2022, Adventure Works experienced a remarkable 233% revenue growth, primarily driven by expanding into the clothing and accessories segments, which proved to be highly profitable.

A deep dive into over 8,000 returned orders uncovered product categories with significantly higher return rates. This pointed to possible quality or customer expectation issues, leading to a recommendation for targeted improvements in product design or customer communication.

Customer segmentation offered additional insight into shifting buyer behavior. There was a 25% increase in low-income customers, while high-income group engagement declined. The majority of buyers remained average earners (46%), suggesting the brand's strongest appeal lies in the mid-market range and strategies should continue to focus there.

The Power BI dashboard developed during this project included 7 KPIs and 15 visuals, and it played an important role across five business units, helping monitor and manage over £3 million in regional sales. Seasonal analysis showed that Q2 and Q4 consistently performed better in sales, indicating ideal windows for marketing pushes and product launches. Lastly, it was clear that the top 10 products accounted for a large portion of total revenue, highlighting the potential benefits of doubling down on high performers in future planning.
