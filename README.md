# Bank-Loan-Report-Analysis
Bank Loan Report Analysis Dashboard: Good Loan vs Bad Loan

📌 Problem Statement

A bank wants to monitor, analyze, and improve loan portfolio performance. Currently, decision-makers lack a centralized view of loan trends, borrower behavior, repayment status, and portfolio risk. The goal is to build an interactive dashboard that provides real-time insights into loan applications, funded amounts, repayments, risk categories, borrower profiles, and portfolio health, helping business teams make data-driven decisions.

🎯 Project Goals

Provide a summary view of loan portfolio health

Track Good vs Bad loan performance

Monitor cash flow, disbursement & repayment trends

Identify high-risk borrower segments

Analyze regional, demographic, and purpose-based trends

Build an interactive dashboard for business decisions

Enable MTD, MoM, and YoY trend monitoring

📌 KPI Requirements (from PPT)
Category	KPI
Portfolio KPIs: Total Loan Applications, Total Funded Amount, Total Amount Received
Trend KPIs	Month-to-Date (MTD) Applications, MTD Funded Amount, MTD Received Amount
Growth KPIs	Month-over-Month (MoM) change
Rate KPIs	Average Interest Rate, Average Debt-to-Income Ratio (DTI)
Risk KPIs: % Good Loan, % Bad Loan, Good Loan – Applications/Funded/Received, Bad Loan – Applications/Funded/Received
Status KPIs (Grid)	Metrics by Loan Status (Funded, Charged Off, Fully Paid, etc.)
📊 Charts Requirement
Dashboard	Visualization	Purpose
Summary Dashboard	KPI Cards + Status Grid	Portfolio health & Good vs Bad performance
Overview Dashboard	Line Chart: Monthly Trend, Seasonality & Lending Patterns
	Filled Map: Region/State	Regional portfolio strength
	Donut: Loan Term	Loan duration distribution
	Bar: Employment Length	Borrower stability impact
	Bar: Loan Purpose	Why customers borrow
	Tree Map: Home Ownership	Ownership vs Lending Behavior
Details Dashboard	Full Data Grid	Loan-level insights & drill-down
🛠️ Tools & Technologies Used
Stack	Tools
Database	MS SQL Server
ETL / Data Cleaning	Power Query
Data Processing & Metrics	SQL, DAX
Visualization	Power BI
Supporting Tools	: Excel / MS Office
🎯 Expected Outcomes

A live interactive Power BI dashboard for all loan insights

Clear visibility of portfolio risk and trends

Faster business decision-making

Identification of high-risk borrower categories

Improved loan recovery and approval policies

Single trusted source of truth (SSOT) for all loan KPIs

🔁 Project Workflow
Data Source → Import to SQL Server → Data Cleaning (SQL/Power Query)
→ Data Modelling (Star Schema + Date Table)
→ DAX Measures & KPI Creation
→ Dashboard Development (Summary, Overview, Details)
→ Formatting, Navigation & UX
→ Publishing & Sharing for Business Use

🚀 Deployment – Finalize & Publish

Create and validate DAX measures

Apply role-level security (if required)

Format visuals and add navigation buttons

Publish dashboard to Power BI Service

Schedule Auto Data Refresh

Share with Business and Management Teams

Monitor usage and improvements

✅ Conclusion

The Bank Loan Analysis Dashboard delivers a comprehensive, visual, and data-driven view of loan performance. It empowers stakeholders to track KPIs, identify risk, understand borrower behavior, and improve decision-making. With automated reporting, interactive visuals, and real-time monitoring, the bank can reduce risk, improve collections, and optimize its lending strategy.
