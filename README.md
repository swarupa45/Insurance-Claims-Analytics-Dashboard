# Insurance-Claims-Analytics-Dashboard
An enterprise-grade insurance analytics solution using SQL and Power BI to solve real-world data profiling, customer risk management, and automated data storytelling challenges.


## 📋 Insurance claims Portfolio Analytics Report

### 📊 Main View: Executive Portfolio Overview

<img width="1341" height="746" alt="Insurance claims" src="https://github.com/user-attachments/assets/46564436-5f12-4465-baa6-d213c18a6721" />

---

### 🔍 View Advanced AI Integration Layout
<details>
<summary><b>💡 Click here to expand and view Page 2 (Smart Narrative & AI Root-Cause Analysis)</b></summary>

### Page 2:  Claims Root-Cause Analysis (AI Decomposition Tree)

<img width="805" height="689" alt="AI decomposition Tree" src="https://github.com/user-attachments/assets/2ec71f58-2899-42d6-937d-f87304dd501b" />


</details>

---

## 🚀 Core Architecture & Tech Stack
* **Data Source:** Microsoft SQL Server (Ingested via Windows Credentials using local dot system notation).
* **ETL & Data Transformation:** Power Query Editor.
* **Data Modeling:** Single Denormalized Fact Table Architecture (Flat Table Strategy).
* **Visualization:** Power BI Desktop (Enhanced Visual Architecture).

## 🎛️ Dynamic UI Filters & Slicers Implemented
Designed an interactive, multi-dimensional filtering layer at the top and left to allow users to slice data on-the-fly:
* **Dropdown Slicers:** `PolicyNumber`, `ClaimNumber`, and `CustomerID` for deep transactional search.
* **Demographic Filter Panels:** A left-aligned `Gender` selector and a dedicated `Claim Status` filter matrix.

## 🛠️ Key Data Transformations Executed
Performed rigorous data quality operations inside Power Query using **Visual Data Profiling (Column Quality, Distribution, and Profile Panes based on the entire dataset)**:

1. **Data Type Harmonization:** Converted `PolicyNumber` and `CustomerID` to Text data types to optimize cross-filtering speeds and prevent invalid aggregations.
2. **Dynamic Segment Creation:** Formulated conditional columns to bin continuous consumer ages into distinct `Age Groups` (Adult, Elder, Young Adult).
3. **Operational Flags:** Programmed analytical conditional status metrics to segregate historical records into `Active` vs `Inactive` policy lifecycles.

## 📊 Core Metrics & Visualizations (As Built)
* **Summary Cards:** Displays total performance metrics at the top header: **Premium Amount**, **Coverage Amount**, and **Claim Amount**.
* **Total Premium Amount by Policy Type:** A horizontal bar chart identifying **Travel Insurance** as the top revenue driver.
* **Count of Active/Inactive Policies:** A donut chart exposing policy status and potential customer churn risk.
* **Claim Amount by Age Group:** An area chart highlighting different consumer segments and risk exposure vectors.
* **Claims Operational Pipeline:** A bottom-right cross-functional Matrix Table isolating financial aggregates across **Pending, Rejected, and Settled** categories sorted by Policy Type.

## 🧠 Advanced AI Integration & Automated Storytelling
To optimize executive decision-making, two native No-Code AI features were implemented in this report layout:
1. **Smart Narrative AI Engine:** Integrated a customized, dynamic Natural Language Generation (NLG) block with a soft container background. This built-in AI automatically reads the operational report layers to output immediate text-based business summaries in plain English, eliminating manual calculation tasks for stakeholders.
2. **AI Decomposition Tree (Root-Cause Analysis):** Configured an interactive machine learning visual to break down the **Total Claim Amount** branch dynamically. By clicking the built-in conditional plus (`+`) options, risk managers can drill down into `PolicyType` and `ClaimStatus` layers on-the-fly, instantly exposing hidden operational bottlenecks.
