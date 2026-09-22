# HR Workforce Analytics Dashboard (Excel + Power Query + VBA)
HR analytics dashboard built on a 1,000-record employee 
dataset, covering headcount, demographics, leave, compensation, and 
skills, with one-click data refresh.

## Overview

This project simulates the kind of workforce reporting an HR or 
management team would use to track department-level and company-wide 
metrics. It was built as the fourth in a series of self-directed Excel 
projects, combining techniques from the earlier ones (PivotTables, 
dashboards, alerts) with Power Query and VBA automation.

## Features

- **Data cleaning** — reviewed the raw dataset for inconsistencies, 
  missing values, and formatting gaps before analysis
- **Multi-dimensional workforce analysis** — headcount by department, 
  location, and job title; gender ratio overall and by age group; 
  leave tracking by role; salary and bonus breakdowns
- **Interactive slicers** — filter by Department, Work Location, or 
  Job Title, with every chart and KPI updating together
- **One-click refresh** — a Refresh button triggers a VBA macro that 
  reloads the Power Query connection and refreshes all PivotTables, 
  with a confirmation message on completion
- **KPI summary cards** — total employees, average performance rating, 
  and employment status breakdown (full-time, part-time, contract)

## Tools & Techniques Used

- Power Query for data loading and refresh
- VBA macro for one-click dashboard refresh
- PivotTables and GETPIVOTDATA
- Slicers with cross-filtering across multiple visuals
- Conditional formatting and dynamic charts

## Screenshots

![Dashboard Overview] <img width="1920" height="1080" alt="dashboard-overview" src="https://github.com/user-attachments/assets/f6acd332-1c7f-4213-a460-75d73f48a788" />

![Filtered View] <img width="1920" height="1080" alt="dashboard-filtered" src="https://github.com/user-attachments/assets/cbed4ccb-fea4-43e4-a9a4-19eb55d950c5" />

## Demo

![Dashboard video] 

https://github.com/user-attachments/assets/ba214d39-cd26-438d-85f0-da2d80e1a282

## Note

This project uses a self-created sample dataset for practice purposes, 
not real company data.
