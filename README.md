# Global Alcohol Consumption (WHO, 2000–2022)

Per-capita alcohol consumption (litres) for 188 countries with full yearly cover

---

## 1. Project Overview

**Dataset / Source:**

KAGGLE

**Time Period Covered: 2000 - 2022**

**Project Type:**

(Exploratory Analysis / Public Policy )

**Data Summary:**

This dataset provides country-level alcohol consumption statistics sourced from the World Health Organization (WHO).

It contains annual per-capita alcohol consumption (litres of pure alcohol per person aged 15+) for 188 countries, covering the period from 2000 to 2022. The dataset is fully balanced, meaning every country has data available for every year in the time range, with no missing values.

The data has been cleaned, and standardized

---

## 2. Business / Stakeholder Context

**Primary Stakeholder:**

WHO / Government policymakers

> This projects is to helps WHO / Government policymakers know where they should focus alcohol reduction policies on.
> 

---

## 3. Business Questions

1. How much alcohol is consumed **globally**?
2. Which countries have **increasing** alcohol consumption over time?
3. What are the **top 10 and bottom 10 countries**?
4.  How is consumption in Europe vs Africa

---

## 4. Data Understanding

**Data Description:**

- 4324 rows , 9 columns

## **COLUMNS**

| COUNTRY | Full country name |
| --- | --- |
| ISO3 | country code (e.g., USA, PAK, DEU) |
| YEAR | Calendar year (2000–2022) |
| SEX | Population group (Both sexes) |
| ALCOHOL LITERS PER CAPITAL | litres of pure alcohol per person per year (age 15+) |
| LOWER_CI | Lower bound of the confidence interval |
| UPPER_CI | Upper bound of the confidence interval |
| CI_WIDTH | Width of the confidence interval (upper_ci - lower_ci) |
| INDICATORCODE | WHO indicator code (SA_0000001688) |

---
<img width="1586" height="801" alt="Screenshot_(63)" src="https://github.com/user-attachments/assets/4423e4d7-ab17-4198-9ce0-1a292dd43247" />

## 4. Data Cleaning & Preparation

**Steps Taken:**

- ISO-3 country codes are preserved
- Full country names are added
- Numeric values are cleaned and validated
- Confidence intervals are included
- Column names are made human-readable

**Columns Added:**

> I added three column
> 

| LIQUOR_750ML | NUMBER OF SMALL LIQUORS |
| --- | --- |
| BEER_330ML | NUMBER OF CAN BEERS |
| LARGE LIQUOR_1.25L | NUMBER OF LARGE LIQUOR |

---
<img width="1831" height="790" alt="Screenshot_2026-01-10_110809" src="https://github.com/user-attachments/assets/2c441f38-39d1-4c65-b4f3-a120c0c29447" />

---

## 5. Key Insights

**Insight 1: Global Consumption Level**
Global alcohol consumption averages **approximately 6 litres per person per year**, indicating a substantial baseline level of alcohol exposure worldwide

**Insight 2:**What are the **top 10  countries**?

<img width="534" height="136" alt="Screenshot_2026-01-12_051924" src="https://github.com/user-attachments/assets/0c685942-80ba-4092-a473-52ca91d60832" />

“Romania has consistently been showing the highest average consumption, suggesting long-term structural patterns rather than short-term fluctuation.”

**Insight 3:**What are the **bottom countries**?

<img width="296" height="312" alt="Screenshot_2026-01-12_052356" src="https://github.com/user-attachments/assets/147a2a29-31d0-450d-927f-8e327940c15b" />

Countries such as **Somalia, Yemen, Bangladesh, Libya, Mauritania, Afghanistan, Sudan, Pakistan, Indonesia, and Egypt** report **extremely low alcohol consumption**, likely influenced by cultural, religious, and regulatory factors.

**Insight 4:** How is consumption in Europe vs Africa

Alcohol consumption in **Europe is significantly higher than in Africa**, this can be due to different cultural norms, income levels, and regulatory environments.

<img width="673" height="355" alt="Screenshot_2026-01-12_055102" src="https://github.com/user-attachments/assets/ed79a027-f7b6-4520-adb2-9e23c9f33c02" />  

<br><br><br>

An interactive Tableau dashboard used to report and explore trends can be found [HERE](https://public.tableau.com/app/profile/ezekiel.nnamani/viz/whoalcoholtableau/Dashboard1).

<img width="1918" height="966" alt="Screenshot_2026-01-13_022844" src="https://github.com/user-attachments/assets/ca1fd1f2-cfd7-4adb-a170-6c56cc965caf" />

---

## 6. Recommendations

### **Recommendation 1: Prioritize High-Consumption Countries for Intervention**

Focus alcohol-control policies (taxation, advertising restrictions, public awareness campaigns) on countries with **consistently high per capita consumption**.

**Who Should Act:**

- World Health Organization (WHO)
- National Ministries of Health in high-consumption countries

**Expected Impact:**

- Reduction in long-term alcohol-related health risks
- More efficient allocation of public health resources

### **Recommendation 2: Preserve Effective Controls in Low-Consumption Countries**

Study and preserve cultural, regulatory, or social factors contributing to **low alcohol consumption** in certain countries.

**Who Should Act:**

- WHO research teams
- Policymakers in low-consumption countries

**Expected Impact:**

- Prevention of future consumption increases
- Transferable policy insights for higher-consumption regions

---

### **Recommendation 3: Target Public Awareness at the Global Average**

Use the **global average of 6 litres per person per year** as a benchmark in public health messaging to contextualize risk and encourage moderation.

**Who Should Act:**

- WHO global communications teams
- NGOs focused on alcohol harm reduction

**Expected Impact:**

- Increased public awareness
- Improved understanding of what constitutes high-risk consumption

---

## 7. Limitations & Risks

**Data Limitations:**

- Missing month by month analysis-The data only contains the year column (e.g 2005)
- Alcohol consumption by gender- The data only contains the a column with just both sexes

**Analysis Limitations:**

> This analysis cannot confidently conclude if and how alcohol is bad for humans
> 

## 8. Tools Used

---

- Python (Pandas)-EDA
- Tableau - REPORTS & DASHBOARD

---

## 9. Future Work & Extensions

If more data were available:

- Which countries may face **higher alcohol-related health risks**?
- Is high consumption correlated with:
    - Mortality rates
    - Liver disease (if external data is added)
- Are countries with declining consumption likely benefiting from:
    - Regulation
    - Education campaigns
- Which gender (male, female) consumes more alcohol

---
