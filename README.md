# Global Progress Toward SDG 7: Affordable and Clean Energy (2000–2022)
[![Power BI Dashboard](https://img.shields.io/badge/Power%20BI-View_Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://app.powerbi.com/view?r=eyJrIjoiMTIzNzhjYTQtMTZiMC00Y2VmLTg1N2MtMWQ5ZjM5NTU4MDc0IiwidCI6ImMzMTBmY2FhLTIzYTMtNDQ4Ny1iN2I2LThlNzNhMDQxNDJhNyJ9)
### 📌 Project Overview

This Power BI dashboard provides a strategic "Dual Track" analysis of the world's progress toward **United Nations Sustainable Development Goal 7 (SDG 7)**. Covering the period from **2000 to 2022** , it tracks the critical balance between expanding energy accessibility (Target 7.1) and accelerating the transition to renewable energy sources (Target 7.2).
The project specifically highlights "The Outliers"—nations, particularly in Africa ("Mission 300"), that are leveraging renewable foundations to leapfrog traditional fossil-fuel-dependent development models.
![SDG 7 Cover Page](https://github.com/racheltran184/PowerBI-Project-2/blob/main/SDG7.png)


---

### 🎯 Target Audience

This dashboard is designed to support decision-making for:

* **Policy Makers & International NGOs:** To identify regions with critical infrastructure gaps (specifically in Sub-Saharan Africa and Asia) and prioritize development aid.


* **Energy Investors:** To analyze markets with high potential—specifically regions where urbanization is outpacing current energy investment, signaling a demand gap.


* **Development Economists:** To study the correlation between GDP, political stability, and energy adoption rates.



---

### 🔍 Key Insights & Findings

#### **1. The Accessibility Gap (Target 7.1)**

* **The Scale of the Crisis:** As of 2022, **2.3 billion people** still lack access to clean cooking fuels, creating a massive health and environmental crisis.


* **Persistent Inequality:** The energy deficit is heavily concentrated in Sub-Saharan Africa. The countries with the lowest electricity access include **Burundi (10.3%)**, **Chad (11.7%)**, and **Malawi (14.0%)**.


* **Success Stories:** Rapid infrastructure scaling is possible. **Afghanistan** increased electricity access by **+80.9%** (from 4.4% to 85.3%) between 2000 and 2022. Similarly, **East Timor** saw near-universal growth, rising from 17.8% to 99.7% (+81.9%).



#### **2. The Renewable Transition (Target 7.2)**

* **The "Outliers" Phenomenon:** African nations are emerging as renewable outliers. While access rates are lower, the energy they *do* generate is increasingly green.


* **Top Improvers:** **Sierra Leone** represents the most dramatic shift, moving from 88.9% fossil fuel dependence in 2000 to **95.0% renewable energy** in 2022—a massive pivot away from carbon dependency.


* **Global Leaders:** Developed nations are also transitioning; **Denmark** increased its renewable share by **+65.9%**, reaching 81.5% in 2022.

---

### 🛠 Technical Implementation

This project utilizes a robust Business Intelligence stack to transform raw data into actionable insights.

* **ETL & Data Cleaning (Excel Power Query):**
* **Technique:** Used Power Query (Get & Transform) to ingest massive datasets from the World Bank and Our World in Data.
* **Transformation:** Performed "Unpivot" operations to transform wide-format year columns (2000–2022) into a single tabular structure suitable for time-series analysis.
* **Cleaning:** Handled null values (e.g., "No data available" for South Sudan in early periods) to ensure accurate visualization without skewing averages.




* **Data Modeling & DAX (Power BI):**
* **Relationships:** Built a Star Schema connecting Fact Tables (Energy Stats) with Dimension Tables (Income Type, Region, Political Stability).


* **DAX Measures:** Created dynamic measures to calculate "Growth %" (Current Year Value - Base Year Value) for the "Top Performers" and "Improvers" leaderboards.




* **Research & Methodology:**
* **Scope:** The analysis covers the period **2000–2022**.


* **Context:** Integrated external research on "Mission 300" and UN SDG targets to provide narrative context to the raw numbers.





---

### 📚 Data Sources

The data for this dashboard was aggregated from the following reputable sources:

* **Political Stability:** [World Bank Indicator (PV.PER.RNK)](https://data.worldbank.org/indicator/PV.PER.RNK)
* **Energy Investment:** [World Bank Indicator (IE.PPI.ENGY.CD)](https://data.worldbank.org/indicator/IE.PPI.ENGY.CD)
* **Urbanization:** [Our World in Data - Urbanization](https://ourworldindata.org/urbanization)
* **Access to Electricity:** [Our World in Data - Energy Access](https://ourworldindata.org/energy-access)
* **Renewable Energy:** [Our World in Data - Renewable Energy](https://ourworldindata.org/renewable-energy)
* **Fossil Fuels:** [Our World in Data - Fossil Fuels](https://ourworldindata.org/fossil-fuels)
* **Electricity Production by Source:** [Our World in Data - Electricity Mix](https://ourworldindata.org/grapher/electricity-prod-source-stacked)
