# AtliQ Hardware: Supply Chain & Finance Analytics Case Study

## Executive Summary
This project represents an end-to-end analytical solution developed during the Codebasics Data Analytics Bootcamp 5.0. I designed a system to automate reporting for a global electronics company, focusing on improving forecast accuracy and financial visibility.

## 🛠️ Technical Competencies
* **Advanced Analytical Queries:** Utilized CTEs and Window Functions (RANK, DENSE_RANK) for market performance analysis.
* **Database Engineering:** Built modular Stored Procedures and User-Defined Functions (UDFs) to streamline complex calculations.
* **Data Automation:** Implemented Triggers and Events to ensure real-time data synchronization between sales and forecast records.
* **Performance Tuning:** Optimized query logic to handle high-volume datasets and overcome server connection limitations.

## 📈 Business Insights & Results

### 1. Supply Chain Optimization
I developed a Forecast Accuracy Report that identifies discrepancies between predicted and actual sales. This allows the business to reduce inventory carrying costs and prevent stockouts.
> **Key Metric:** Forecast Accuracy = 100% - Absolute Error Percentage.

### 2. Financial Reporting
Automated the generation of Monthly Gross Sales reports for major customers (e.g., Croma). I also implemented a "Market Badge" system to reward high-performing regions (Gold vs. Silver status).

## 📊 Project Visuals & Reports

### Supply Chain Performance
The following report identifies forecast accuracy across different markets. This helps the supply chain team pinpoint where inventory planning needs improvement.
![Forecast Accuracy Report](https://github.com/pavanmajji18/Atliq-Hardware-SQL-Analytics/blob/main/Forecast%20Accuracy%20Report.png)

### Finance: Market Performance Badging
By automating the 'Market Badge' system, the business can instantly see which regions reached 'Gold' status based on a 5M unit sales threshold.
![Market Badge Output](https://github.com/pavanmajji18/Atliq-Hardware-SQL-Analytics/blob/main/Market%20Badge%20Output.png)



### Sales: Top Performing Products
Using DENSE_RANK window functions, this report highlights the top 3 products in each division to help focus marketing efforts.
![Top Products Report](https://github.com/pavanmajji18/Atliq-Hardware-SQL-Analytics/blob/main/Top%20Products%20Report.png)

## 🚀 Technical Challenges Overcome
* **Scalability:** Addressed connection timeouts during heavy data consolidation by implementing staged data insertion strategies.
* **Data Integrity:** Used Database Triggers to maintain a helper table (`fact_act_est`), ensuring that analytics are always based on the most recent sales data.

---
*Note: Per course policy, source code and raw data files are not provided in this repository. This documentation serves as a summary of the technical methodologies applied.*
