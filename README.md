# Atliq Mart Supply Chain Analysis Dashboard

## Overview
AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities Surat, Ahmedabad and Vadodra. They want to expand to other metro/tier1 cities in the next 2 years.

AtliQ Mart is currently facing a problem where a few key customers did not extend the annual contract due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ’On time’ and ‘In Full’ delivery service level for all the customers on a daily basis so that they can respond swiftly to these issues.

The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘on-time delivery (OT) %’, ‘In-full delivery (IF) %’ and OnTime in full (OTIF) % of the customer orders on a daily basis against the target service level set for each customer.

## Dashboard Sections
![Dashboard](https://github.com/mothethomas/Supply-Chain-Analysis/blob/main/Dashboard/supply_chain_analysis.jpg)
## Key Performance Indicators (KPIs)
OT% (On-Time Delivery): 59.0%

This percentage indicates that 59% of orders are being delivered on time.
IF% (In-Full Delivery): 52.8%

This percentage shows that 52.8% of orders are being delivered in full.
OTIF% (On-Time In-Full Delivery): 29.0%

This percentage represents that only 29% of orders are being delivered both on time and in full.
OT% vs Target: 66.0%

This metric compares the actual on-time delivery percentage against the target, indicating that the current performance is 66% of the target.
IF% vs Target: 96.6%

This metric compares the actual in-full delivery percentage against the target, indicating that the current performance is 96.6% of the target.

### 2. City-wise Performance
- Displays OT%, IF%, and OTIF% vs their respective targets for Surat, Ahmedabad, and Vadodara.
- Helps identify which cities are performing well and which need improvement.

### 3. Filters
- Allows filtering data by dimensions such as date, product, and city.
- Helps in narrowing down data specific to the user's needs.

### 4. Product Insights
- A table showcasing individual product performance with columns:
  - **Product Name**
  - **Ship Date**
  - **OT%**
  - **IF%**
  - **OTIF%**
  - **ADDD (Average Days Delivery Delay)**
- Helps in understanding which products are causing delays or not being delivered in full.

### 5. Customer Insights
- A detailed view of customer performance with columns:
  - **Customer Name**
  - **City**
  - **OT%**
  - **IF%**
  - **OTIF%**
  - **ADDD**
- Highlighted values indicate customers who are facing significant service issues.
- Allows for targeted interventions to improve customer service.

### 6. Performance Trend
- A line chart depicting the trend of OTIF% performance over time.
- Helps in identifying any patterns or anomalies in performance.

## How to Use the Dashboard
1. **View KPIs**: Quickly glance at the top section to understand the overall performance.
2. **Analyze City Performance**: Use the city-wise performance section to compare how different cities are performing against their targets.
3. **Utilize Filters**: Apply filters on the right side to narrow down data specific to your needs (e.g., by date, product, or city).
4. **Examine Product Insights**: Scroll to the product insights section to identify which products are causing delays or incomplete deliveries.
5. **Investigate Customer Insights**: Use the customer insights table to pinpoint customers who are experiencing service issues.
6. **Monitor Performance Trends**: Observe the line chart at the bottom to identify any trends or patterns in OTIF% over time.

## Conclusion
This dashboard provides a comprehensive view of AtliQ Mart's supply chain performance, helping management identify areas for improvement and make data-driven decisions to enhance service levels.
