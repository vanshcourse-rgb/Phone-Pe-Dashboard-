📱 PhonePe Transaction Analysis Dashboard (Power BI)

An interactive Power BI dashboard analyzing PhonePe transaction data across four major service categories — Insurance, Loans, Money Transfer, and Recharge & Bills. The dashboard tracks transaction volume, payment success/failure rates, failure reasons, and monthly trends to surface actionable business insights.


📌 Project Overview

Digital payment platforms process millions of transactions daily, and understanding where and why transactions fail is critical to improving customer experience and reducing revenue loss. This dashboard consolidates transaction data across PhonePe's core services into a single interactive report, allowing stakeholders to monitor performance at a glance and drill into specific services.

The dashboard includes:


Overall transaction summary (Home page)
Service-wise breakdown: Insurance, Loans, Money Transfer, Recharge & Bills
Payment success vs failure analysis
Failure reason breakdown (Wrong PIN, Server Error, Insufficient Amount, Wrong Info, Bank Denied)
Monthly transaction amount trends
Date range filtering across all pages



🎯 Objectives


Consolidate transaction data across multiple services into one report
Identify total and failed transaction volume, and the top reasons for failure
Compare transaction amount and count across services (Loans, Insurance, Money Transfer, Recharge & Bills)
Track monthly transaction trends to spot seasonality or anomalies
Enable interactive filtering by date range for ad-hoc analysis



🛠️ Tools & Technologies


Power BI Desktop — data modeling, DAX measures, report design
DAX — for KPIs like Total Amount, Success Rate, Failed Transactions
Power Query — data cleaning and transformation



📊 Dashboard Pages

1. Home (Overview)


Total Amount: 3,333M
Successful Transactions: 288K
Total Transactions: 300K
Failed Transactions: 12K
Service vs Amount comparison (Loans highest at 2.53bn)
Failed payment reasons breakdown
Monthly transaction amount trend


2. Insurance


Total Amount: 491M
Payment success rate: 95.75%
Transaction breakdown by insurance type (Auto, Family, Bike, Health)
Monthly transaction trend


3. Loans


Total Amount: 2,431M
Payment success rate: 95.95%
Breakdown by loan type: Auto Loan, Mutual Funds, Gold Loan, Credit Score
Monthly transaction trend


4. Money Transaction


Total Amount: 363M
Transaction Count: 1,50,000
Payment success rate: 95.98%
Breakdown by transfer type: UPI ID, Self Account, QR Code, Mobile Number
Monthly transaction trend


5. Recharge & Bills


Total Amount: 48.71M
Payment success rate: 96.16%
Breakdown by category: Electricity, DTH, Mobile, Cable TV
Monthly transaction trend



💡 Key Insights


Loans is the highest revenue-generating service (2.53bn), far ahead of Insurance, Money Transfer, and Recharge & Bills combined
Across all services, payment success rate stays consistently high (~95–96%), indicating a stable payment infrastructure
The most common failure reasons across services are Server Error, Wrong PIN, and Insufficient Amount
Bank Denied and Wrong Info appear as failure reasons only in specific services (Home overview and Loans respectively), suggesting service-specific failure patterns worth investigating
Monthly transaction amounts fluctuate moderately across all services without a single sustained peak/dip month, suggesting relatively stable demand year-round



🚀 How to Use


Clone/download this repository
Open the .pbix file in Power BI Desktop
Use the Date Range filter on each page to explore specific time periods
Navigate between pages using the tabs at the bottom (Home, Insurance, Loans, Money Transaction, Recharge and Bills)



📁 Project Files

FileDescriptionPhonePe.pbixPower BI dashboard fileScreenshot (122–126).pngPreview images of each dashboard page


🔮 Future Improvements


Add a drill-through page for root-cause analysis of failed transactions
Add year-over-year comparison once multi-year data is available
Publish to Power BI Service for live sharing and scheduled refresh
