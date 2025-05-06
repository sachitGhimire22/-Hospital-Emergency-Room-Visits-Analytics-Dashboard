# 🏥 Hospital Emergency Room Visits Analytics Dashboard



Welcome to the Hospital Emergency Room Visits Analytics Dashboard



## 📝 Introduction

The Emergency Department (ED) plays a critical role in delivering immediate care to patients in urgent need. With a commitment to improving patient outcomes, operational efficiency, and resource planning, our team has been tasked with conducting a comprehensive analysis of emergency room visits.

This analysis is based on the data provided by the hospital, covering the period from **April 2023 to December 2024**, and aims to uncover key trends, performance metrics, and actionable insights to support informed decision-making.

**Insights and recommendations are provided on the following key areas:**

### 📆 Patient Demographics

**Focus: Who is visiting the ER?**

* Patient Age Group Distribution
* Patient Gender Distribution
* Patient Race Breakdown
* Total Patients, Male Patients, Female Patients

### ⏳ Visit Volume and Flow

**Focus: How many visits occur and how they trend over time?**

* ER Visits Trend Over Time
* Department Referral Breakdown
* Patient Admission Status

### ⚖️ Operational Efficiency

**Focus: How well is the ER functioning?**

* Average Wait Time (Min)
* Patient Wait Time Distribution (Min)

### 😊 Patient Experience & Satisfaction

**Focus: How do patients feel about their ER experience?**

* Average Satisfaction
* Patient Satisfaction Trend

An interactive Tableau dashboard used to report and explore trends can be found here: \[Link]



## 📊 Data Structure & Initial Checks

The hospital's data infrastructure consists of two primary tables used in this dashboard, with a total of **X records**. These tables form the foundation for generating insights and trends related to emergency room performance:

**Table 1: Hospital ER\_Data**

* Visit Date
* Patient ID
* Gender, Age, Race
* Admission Status
* Referral Department
* Wait Time (minutes)
* Satisfaction Score

**Table 2: Date Table**

* A structured calendar table used to support time-based analyses.
* Ensures correct sorting and filtering of date-related visuals like trends and distributions over time.

![Screenshot 2025-05-06 125211](https://github.com/user-attachments/assets/b27f634a-e50c-4079-a49b-d47f20cd3f63)


## 📃 Executive Summary

### ✨ Overview of Findings

The emergency room dashboard reveals three key insights:

1. Patient volume is high and evenly split across genders, with 50% requiring admission—highlighting the ER’s critical role in initial patient care.
2. While average wait times are moderate, certain departments like Neurology and Physiotherapy experience higher delays, indicating areas for operational improvement.
3. Patient satisfaction remains impressively high across all demographics, suggesting strong overall performance, particularly among Pacific Islander and African American patients.

![image](https://github.com/user-attachments/assets/07bdd480-309a-4c2d-9d8b-1a6f58fada4e)

## 🔍 Insights

### 1. 🤔 Patient Volume

* Total ER visits: **9,216** (April 2023 - December 2024)

### 2. ♂️♀️ Gender Distribution

* Male Patients: **4,705** (51%)
* Female Patients: **4,487** (48.6%)
* Not Confirmed: **0.26%**
* → Reflects equitable healthcare access across gender demographics

### 3. ⛨️ Admissions Overview

* Exactly **50%** of all ER visits resulted in hospital admission
* → Suggests effective triage and necessary escalation for half the cases

### 4. ⏱️ Average Wait Time

* Average wait time: **35.26 minutes**
* → Indicates moderate queue times with potential for optimization

### 5. 🌟 Patient Satisfaction

* Overall satisfaction: **4.99/5**
* → High service delivery and care standards

### 6. 🏥 Department Referrals

* Most cases not referred (**5.4K**), resolved within ER
* Top referral departments:

  * General Practice: **1.8K**
  * Orthopedics: **1.0K**

### 7. ⏳ Wait Time by Department

* Highest:

  * Neurology: **36.8 min**
  * Physiotherapy: **36.57 min**
* Lowest:

  * Renal: **34.7 min**
  * General Practice: **34.9 min**
* → Targets for efficiency improvement

### 8. 👶👧 Age Group Distribution

* Fairly uniform across brackets
* 20-29 age group leads with **1,200** visits

### 9. 🌍 Race-Based Insights

* Most frequent visitors:

  * White: **2.6K**
  * African Americans: **2.0K**
  * Multi-racial: **1.6K**
* → Potential for targeted outreach and programs

### 10. 😊 Satisfaction by Race

* Pacific Islanders: **5.33**
* African Americans: **5.07**
* → Suggests highly effective care delivery for these groups



## 🔗 Actionable Recommendations ✨

### 1. ⚖️ Optimize Departmental Resources

* Neurology and Physiotherapy report highest wait times (36.80 and 36.57 min)
* → Allocate additional staff or streamline triage procedures in these departments

### 2. 🙌 Improve Patient Experience in General Practice

* General Practice receives 1.8K referrals; improvement needed in satisfaction
* → Real-time feedback, enhanced communication, and staff training

### 3. 🌍 Enhance Services to Minority Racial Groups

* Pacific Islanders and Native American/Alaska Natives have highest satisfaction
* → Study and replicate successful care delivery models in other demographics

### 4. 🏥 Streamline Admission Processes

* 50% admission rate
* → Use predictive analytics to improve bed and staffing readiness

### 5. 📈 Improve Data Quality

* Incomplete fields (e.g., Gender: Not Confirmed)
* → Enforce stricter data validation and entry protocols



## 🙏 THANK YOU

Explore my other projects too ✨
