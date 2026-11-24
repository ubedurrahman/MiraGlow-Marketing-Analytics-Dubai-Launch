#### 📊 MiraGlow Marketing Analytics & Brand Launch in Dubai

An end-to-end marketing performance audit and international expansion simulation built with **Excel** and **Power BI**. This project analyzes 8 months of domestic D2C skincare performance in India (**INR**) to uncover channel inefficiencies and designs a data-backed **50,000 AED** go-to-market launch plan for **Dubai, UAE**. 

#### 🎯 Business Problem & Objectives

MiraGlow, an Indian Ayurvedic skincare brand, wanted to optimize domestic ad spend before expanding into the GCC market. Leadership needed answers to three core questions: 

1. **Channel Efficiency:** Which marketing channels generate sustainable return on ad spend (ROAS) vs. draining customer acquisition budget (CAC)?
2. **Product & Customer Drivers:** Which SKUs and customer segments drive core revenue vs. first-time acquisition?
3. **Brand Launch in Dubai Strategy:** How should a **50,000 AED** 90-day launch budget be allocated across UAE channels based on proven domestic unit economics?

#### 🛠️ Tech Stack & Data Architecture

* **Data Modeling & ETL:** Microsoft Excel & Power Query (trimming whitespace, standardizing keys, enforcing data types, removing errors/nulls).
* **Schema Design:** **Star Schema** connecting 1 Fact table (Fact_Marketing_Performance) with 3 Dimension tables (Dim_Channels, Dim_Products, Dim_Customers) using single-direction 1:* relationships, plus a standalone forecast table (Dubai_Launch_Forecast).
* **Analytics & KPIs (DAX):** Dedicated _Measures table computing Total Revenue, Total Ad Spend, ROAS, CAC, Conversion Rate, AOV, and multi-currency UAE forecast KPIs (INR & AED).
* **Visualization:** 3-page interactive Power BI Executive Report.

#### 📈 Dashboard Overview & Key Insights

#### Page 1: Executive Overview (India Baseline — INR)

 

* **8-Month Performance:** **₹2,76,962** Total Revenue | **₹74,800** Ad Spend | **3.70x** Blended ROAS | **₹314** Blended CAC | **1.62%** Conversion Rate.
* **Product-Segment Fit:** *Kumkumadi Face Oil* is the top revenue generator driven by **VIP High-Value** customers, while *Neem Purifying Cleanser* serves as the primary acquisition SKU for **First-Time Buyers**.

#### Page 2: Channel Efficiency & ROI (CAC vs. ROAS)

 

* **Paid Social Bottleneck:** Consumes **₹29,900** (40% of spend) with a **0.73%** conversion rate, **₹767 CAC**, and **1.05x ROAS**.
* **High-Intent & Retention Winners:** **Paid Search** delivers **₹93,533** at a **2.63x ROAS** and **₹1,396 AOV**, while **Email** achieves **14.40x ROAS** at an **₹80 CAC**.

#### Page 3: Brand Launch in Dubai (UAE Forecast — AED)

 

* **90-Day GTM Projection:** **50,000 AED** Budget → **95,000 AED** Projected Revenue (**1.90x** Blended ROAS | **121.95 AED** Blended CAC).
* **Channel Allocation:** Prioritizes **Google UAE Paid Search (44%)** and **Dubai Expat/Emirati Micro-Influencers (30%)**, supported by **Noon/Amazon.ae (16%)** and **VIP Launch Email/Referrals (10%)**.

#### 💡 Strategic Recommendations

1. **Reallocate 30% of Domestic Paid Social Budget (₹9,000) to Paid Search:** Shift spend from low-converting broad social ads into high-intent search terms for *Kumkumadi Face Oil* and *Saffron Night Cream*.
2. **Deploy Automated 45-Day Replenishment Email Flows:** Convert *Neem Cleanser* first-time buyers into repeat VIP customers at < ₹100 CAC.
3. **Execute a Search- & Marketplace-Led Dubai Launch:** Avoid broad social awareness spend in the UAE in favor of high-intent Google UAE search, Noon/Amazon.ae listings, and targeted beauty creators.

**Note:** *Source .pbix and raw dataset files are stored privately to protect intellectual property and are available for live walkthroughs during interviews.*
© 2026 Md Ubed Ur Rahman. All Rights Reserved. Shared for portfolio viewing purposes only; copying, redistribution, or reuse without explicit permission is prohibited.

