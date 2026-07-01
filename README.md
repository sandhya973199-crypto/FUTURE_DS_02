# Telco Customer Retention & Churn Analysis

## 📌 Project Overview
Customer churn directly impacts predictable revenue streams and operational scalability for subscription-based businesses. This project analyzes customer data from a telecommunications provider to identify dominant churn patterns, decode structural friction points, and isolate critical retention drivers. 

The analysis transforms raw customer data into prioritized, data-driven business recommendations tailored for a Product Manager, Business Stakeholder, or Startup Founder.

## 🛠️ Tools & Technologies Used
* **Microsoft Excel**: Advanced Pivot Tables, Data Grouping (Tenure Cohorts), Custom Visualizations, Data Cleaning, and Executive Reporting.

---

## 📂 Repository Structure
* 📑 **`Telco-Customer-Churn.xlsx`**: The primary operational workbook containing cleaned source data and detailed pivot tables structured in professional layout order (Left to Right):
    1. `FINAL REPORT`: Executive summary, high-level KPIs, and strategic recommendations (Main Dashboard layer).
    2. `Telco-Customer-Chur`: The primary, cleaned raw data source sheet.
    3. `TENURE CHURN`: Lifecycle cohort segmentation and trend visualizations.
    4. `CONTRACT CHURN`: Plan-type risk analysis.
    5. `INTERNET SERVICE`: Product-line churn diagnostics.
    6. `PAYMENT CHURN`: Billing method friction tracking.
* 📝 **`README.md`**: Project documentation and key insights summary.

---

## 📊 Key Analytical Insights

### 1. Macro Metrics
* **Total Customer Base Analyzed**: 7,043 customers
* **Total Churned Volume**: 1,869 customers
* **Global Baseline Churn Rate**: 26.54%

### 2. Deep-Dive Segment Vulnerabilities
* **Customer Lifecycle Risk**: Churn is heavily front-loaded during initial adoption. **48.28%** of all customers terminate their subscriptions within the first 11 months. Conversely, long-term brand equity is highly resilient; customers who reach a tenure of 5+ years (60–72 months) display a minimal churn rate of just **6.68%**.
* **Contract Vulnerability**: Customers on Month-to-Month contracts represent a severe volatility point, accounting for **88.5%** of all corporate churn (1,655 out of 1,869 churned users).
* **Service Quality Anomalies**: High-speed Fiber Optic subscribers exhibit an alarmingly high churn rate, contributing **69.4%** to total churn volume (1,297 customers), indicating potential onboarding friction or pricing-to-value gaps.
* **Payment Friction**: Manual billing via Electronic Checks triggers the highest transaction-layer drop-off, accounting for **57.3%** of total churn (1,071 customers) compared to automated credit card or bank transfer options.

---

## 💡 Strategic Recommendations

Based on the quantitative trends surfaced in this dataset, the following strategic plays are recommended to stabilize monthly recurring revenue (MRR):

1. **First-Year Engagement Programs**: Because nearly half of our customer loss occurs in the 0–11 month window, introduce milestone loyalty incentives (e.g., a "6-Month Account Credit") to bridge early-stage users into more stable, mature tenure brackets.
2. **Contract Migration Framework**: Design targeted, in-app promotions offering small, fixed discounts to seamlessly transition volatile Month-to-Month subscribers onto predictable 1-Year or 2-Year agreements.
3. **Fiber Optic Network Technical Audit**: Task the engineering and customer success teams to audit the Fiber Optic onboarding pipeline to fix technical issues or price-perception pain points causing premium users to drop off.
4. **Auto-Pay Incentives**: Roll out a one-time invoice discount ($5) to motivate manual Electronic Check users to link their credit card or bank account for automated billing.

