# Cyclistic Bike Share Analysis
### Google Data Analytics Capstone Case Study

## Project Overview

This project was completed as part of the Google Data Analytics Professional Certificate Capstone.

The objective was to analyze Cyclistic bike-share data and identify behavioral differences between annual members and casual riders. Insights from the analysis were used to develop data-driven recommendations for increasing annual membership conversions.

---

## Business Task

**How do annual members and casual riders use Cyclistic bikes differently, and how can Cyclistic convert more casual riders into annual members?**

---

## Dataset

### Source
- Divvy Trip Data
- Lyft Bikes and Scooters LLC
- Public Dataset: https://divvy-tripdata.s3.amazonaws.com/index.html

### Time Period
**November 2025 – October 2026**

### Dataset Size

| Dataset | Rows |
|----------|----------:|
| Raw Dataset | 6,294,451 |
| Cleaned Dataset | 6,288,920 |

---

## Tools Used

- Microsoft Excel
- Python (Pandas)
- Kaggle
- Tableau

---

## Data Cleaning Summary

The following data preparation steps were performed:

- Merged 12 monthly datasets into a single dataset
- Converted datetime fields
- Created derived features:
  - `ride_length`
  - `date`
  - `month`
  - `day_of_week`
  - `hour`
- Removed 35 duplicate records
- Removed 29 negative ride durations
- Removed 5,148 ride records exceeding 24 hours
- Removed 319 records with missing geographic coordinates
- Retained station-related null values to avoid significant data loss

**Final cleaned dataset:** 6,288,920 rides

---

## Tableau Dashboard

### Dashboard Preview

<img width="1249" height="999" alt="bikeshare_analysis_dashboard" src="https://github.com/user-attachments/assets/fac4ff49-b55c-434e-9f6f-12a79e8fab7b" />

### Interactive Dashboard

Tableau Public:
https://public.tableau.com/views/CyclisticRideSharingExecutiveDashboard/ExecutiveOverview

---

## Key Findings

### 1. Members Account for Most Usage

- Members: **64.46%**
- Casual Riders: **35.54%**

### 2. Casual Riders Take Longer Trips

| Rider Type | Average Ride Length |
|------------|--------------------:|
| Casual | 17.40 min |
| Member | 11.87 min |

### 3. Members Display Commuting Behavior

- Highest activity: Tuesday–Thursday
- Peak usage: Approximately 8 AM and 5 PM

### 4. Casual Riders Display Recreational Behavior

- Highest activity: Saturday and Sunday
- Longer average ride durations

### 5. Ridership Is Seasonal

- Highest activity: July–August
- Lowest activity: Winter months

---

## Recommendations

### 1. Target Weekend Casual Riders

Offer:
- Membership trials
- Weekend upgrade promotions
- First-month membership discounts

### 2. Launch Summer Membership Campaigns

Focus marketing efforts during peak riding months when casual ridership is highest.

### 3. Promote Convenience and Cost Savings

Highlight:
- Daily transportation benefits
- Convenience
- Long-term savings associated with annual memberships

---

## Conclusion

Members primarily use Cyclistic as a transportation solution, while casual riders are more likely to use the service for leisure and recreation.

To increase membership conversions, Cyclistic should focus on active casual riders through seasonal promotions, weekend campaigns, and messaging that emphasizes convenience and long-term value.

---
