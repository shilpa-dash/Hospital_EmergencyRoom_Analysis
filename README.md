# Hospital Emergency Room Dashboard – Power BI

# Overview
An interactive Power BI dashboard built to analyze Hospital Emergency Room (ER) operations, patient demographics, and service performance. The report consolidates **9,200+ patient encounter records** into a 3-page dashboard for monthly tracking, consolidated analysis, and patient-level drill-down.

## Dashboard Pages

### 1. Monthly View
Tracks monthly performance with Year/Month filters showing:
- No. of Patients, Average Wait Time, Patient Satisfaction Score, No. of Patients Referred
- Patient Admission Status (Admitted vs Not Admitted)
- % of Patients seen within 30 minutes (SLA target tracking)
- Patient breakdown by Age Group, Gender, Race, and Department Referral
- No. of Patients by Day and Hour (heatmap matrix)

### 2. Consolidated View
A full-period (Apr 2023 – Oct 2024) rollup of the same KPIs and breakdowns, with a date range slicer for custom period analysis.

### 3. Patient Details
A detailed, drillable table listing individual patient records — Patient ID, Name, Gender, Age, Admission Date, Race, Wait Time, Department Referral, and Admission Status — for case-level review.

## Key Metrics Tracked
| Metric | Description |
|---|---|
| No. of Patients | Total ER patient volume |
| Average Wait Time | Mean time (minutes) before patients are seen |
| Patient Satisfaction Score | Average satisfaction rating (out of 5) |
| No. of Patients Referred | Patients referred to specific departments |
| % Seen Within 30 Min | SLA compliance metric for ER response time |
| Admission Status | Admitted vs Not Admitted split |

## Tools & Techniques
- **Power BI Desktop** – report design and data visualization
- **Data Modeling** – relationship between Date Table and Hospital ER_Data
- **Visuals Used** – KPI cards, donut charts, bar charts, matrix/heatmap, sparklines
- **Interactivity** – slicers (date range, year, month), drill-through navigation across report pages


## Screenshots
