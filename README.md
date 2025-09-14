# Nordic E-Commerce Customer Behavior Analysis

Dataset

~20,000 transactions across Sweden, Denmark, Norway, and Finland

Fields: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

Derived field: Revenue = Quantity × UnitPrice

## Methods

Data Cleaning → removed missing values, cancellations, and created revenue metric

Exploratory Analysis → revenue by country, top products, monthly trends, spending distribution

Statistical Checks → outlier detection (IQR), correlation analysis

Customer Segmentation → RFM metrics with KMeans clustering

## Results

Revenue by Country: Sweden generated ≈ 42% of revenue, followed by Denmark (27%), Norway (19%), and Finland (12%).

Top Products: The 10 best-selling products made up ≈ 30% of total units sold → evidence of the Pareto principle.

Seasonality: Monthly revenue showed holiday peaks ≈ 40% above the yearly average, with year-over-year growth of ≈ 18%.

Customer Spend: Median spend per customer was modest (~€220), but the top quartile spent 3.5× higher.

Top 5% Customers: This group contributed ≈ 48% of all revenue, confirming reliance on an elite few.

Outliers: ~0.9% of transactions were extreme bulk purchases, skewing revenue upward by ≈ 12%.

Correlation: Quantity strongly correlated with revenue (r ≈ 0.85), while price vs. quantity was weakly negative (r ≈ –0.18).

Segmentation: RFM clustering grouped customers into 4 segments:

Loyal (25%) → 45% of revenue

High-Value (15%) → 30% of revenue

At-Risk (35%) → 20% of revenue

Low-Engagement (25%) → 5% of revenue

## Visualizations

Revenue by country (bar chart)

Top 10 products (bar chart)

Monthly revenue trend (line chart)

Average spend distribution (histogram)

Top 5% vs 95% customers (donut chart)

Revenue outliers (boxplot)

Correlation heatmap

RFM clusters (scatterplot)

## Built With

Python 3

pandas, numpy

matplotlib, seaborn

scikit-learn (KMeans)

Jupyter/Colab

## Final Insights

Sweden is the priority market, driving the largest revenue share

A few products and customers dominate sales → inventory and loyalty programs are critical

Seasonal demand peaks highlight the need for forecast-driven planning

Outlier detection can flag potential fraud or wholesale anomalies

RFM segmentation enables targeted strategies: retain loyal, re-engage at-risk, and grow high-value customers


## Contact Information:
- Email: teerthgupta19@gmail.com
- LinkedIn:[https://www.linkedin.com/in/teerth-gupta-52a248243/]
- Name-Teerth Gupta
