# -Business-Insights-360-Power-BI-Dashboard

🏢 Project Background

AtliQ Hardware has been growing rapidly and expanding into global markets. To stay competitive with industry leaders already leveraging advanced analytics, the company decided to adopt Power BI for data-driven decision-making.

This project was completed as part of the Codebasics Bootcamp – Business Insights 360 and focuses on building an interactive, end-to-end BI dashboard that delivers actionable insights to key business stakeholders.

🎯 Project Objective

To design a centralized Power BI dashboard that answers critical business questions across multiple departments, enabling leadership to make faster, smarter, and more confident decisions.

📌 Key Business Domains Covered

The dashboard provides insights across the following functions:

Finance – P&L analysis, Net Sales trends, profitability metrics

Sales – Customer and product performance, Gross Margin %, unit economics

Marketing – Market, region, product & customer-level insights

Supply Chain – Forecast accuracy, net error, and demand planning performance

Executive – High-level KPIs and performance overview

Product – Top & bottom products by YoY GM% growth and post-discount analysis

🛠 Tools & Technologies

Power BI – Dashboard development & visualization

Power Query – Data cleaning and transformation

DAX – Measures, KPIs, and dynamic calculations

Data Modeling – Snowflake schema design

SQL – Data extraction, validation, and business-focused queries

Microsoft Excel – Initial data exploration and validation

DAX (Data Analysis Expressions) – Creating calculated measures, KPIs, time intelligence, and dynamic calculations

🛠️ Power BI Features & Capabilities

Data Cleaning & Transformation using Power Query for accurate and analysis-ready datasets

Snowflake Data Modeling to ensure efficient relationships and optimal report performance

DAX Measures & KPIs for business metrics, time intelligence, and dynamic calculations

Dynamic Titles that automatically update based on applied filters and slicers

Conditional Formatting using icons and color rules to highlight key performance variations

Bookmarks & Navigation Buttons for smooth, user-friendly report navigation

Drill-Through Pages for deep-dive analysis at granular levels

Custom Tooltips to provide contextual insights without cluttering visuals

Date Table Creation using M Language for accurate time-based analysis

KPI Indicators for quick performance assessment at a glance

Data Validation Techniques to ensure consistency, reliability, and data accuracy

🏢 Company Background

AtliQ Hardware is a global seller of computers and accessories, operating through three primary sales channels:

🏬 Retailers

🛒 Direct Sales

📦 Distributors

Recently, the company incurred significant losses due to a poorly planned store expansion in the USA, which relied primarily on survey-based insights and Excel analysis. This experience highlighted the limitations of traditional reporting and created an urgent need for a robust analytics system to minimize guesswork and support data-driven decision-making.

To address this challenge, AtliQ Hardware decided to implement Power BI–driven analytics, enabling stakeholders to gain real-time visibility into business performance across regions, products, and customers.

📂 Dataset Details

The dataset used in this project represents real-world business scenarios and includes 1.5M+ records spanning multiple functional areas such as Finance, Sales, Marketing, Supply Chain, and Products.

It consists of:

Fact tables capturing transactional data (sales, forecasts, discounts, performance metrics)

Dimension tables including customers, products, markets, dates, and channels

Historical data designed to support trend analysis and YoY comparisons

The data was cleaned, validated, and modeled using a snowflake schema to ensure accuracy, performance, and scalability within Power BI.

The project uses two databases provided in the Bootcamp: gdb041 and gdb056.
Together, they cover customers, products, markets, sales, forecasts, and associated costs.

🗄️ gdb041
dim_customer

27 markets (e.g., India, USA, Spain)
75 unique customers
Platforms: Brick & Mortar (offline), E-commerce (Amazon, Flipkart, etc.)
Channels: Retailer, Direct, Distributor
dim_market

Market details grouped into 7 sub-zones and 4 regions (APAC, EU, NAN, LATAM)
dim_product

Divisions: P&A (Peripherals & Accessories), PC (Notebooks & Desktops), N&S (Networking & Storage)
14 product categories (e.g., Internal HDD, Keyboard) with multiple variants
fact_forecast_monthly

Monthly demand forecasts by customer
Used to compare forecast vs. actual sales for inventory planning
fact_sales_monthly

Monthly actual sales quantities
Helps track performance against forecast
🗄️ gdb056
freight_cost – Logistics and freight expenses by market & fiscal year
gross_price – Gross product prices by product code
manufacturing_cost – Yearly manufacturing costs per product
pre_invoice_deductions – Trade discounts applied before invoicing (customer & year level)
post_invoice_deductions – Discounts and claims applied after invoicing
