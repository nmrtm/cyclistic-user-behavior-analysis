# 🚲 Cyclistic User Behavior Analysis

## 📍 Project Overview

In this project, I analyzed a fictional bike share company’s usage data using **R** and **Tableau** to identify trends and strategies for converting **casual riders into annual members**.

Findings showed that casual riders tend to take longer rides, especially in the summer. Based on the insights, I proposed **targeted marketing campaigns and membership offers** to improve user retention and engagement.

---

## 🏢 Company Profile

Cyclistic is a fictional bike-share company based in Chicago with:
- 5,800+ bicycles and 600+ docking stations
- Primarily traditional bikes, with 8% electric-assisted usage
- Users who mostly ride for leisure, with 30% commuting regularly

The marketing team's goal is to understand usage patterns between **casual riders** (single-ride or day-pass) and **annual members**, in order to grow memberships.

---

## ❓ Business Task

> *How do annual members and casual riders use Cyclistic bikes differently?*

## 🎯 Business Objective

> *Identify trends that can help convert casual riders into annual members.*

---

## 🔍 Data Source

- Public Divvy trip data (used under Cyclistic's fictional context)  
- 📂 [Data source link](https://divvy-tripdata.s3.amazonaws.com/index.html)

---

## 🛠️ Tools Used

- **R** (R Studio) for data cleaning, transformation, and analysis  
  - 📄 [R analysis on Kaggle](https://www.kaggle.com/code/namratamuralidharan/gwg-analytics-cyclistic-case-study)
- **Tableau** for visual storytelling  
  - 📊 [Visual slide deck on Tableau Public](https://public.tableau.com/views/Cyclistic-BikeShareCaseStudy_16966064333810/CyclisticBikeShare)

---

## 🔬 Process Overview

1. Cleaned and merged multiple monthly datasets in R
2. Conducted exploratory data analysis (EDA) on:
   - Ride duration
   - Seasonality and peak hours
   - Weekday vs weekend usage
   - Bike and station preferences
3. Exported clean dataset to Tableau Public
4. Built a **slide deck-style visual story** to present business context, methodology, key findings, insights, and recommendations for stakeholders

---

## 📈 Key Findings

### 🕒 Ride Duration & Timing
- Casual riders take **longer rides**, especially during weekends and summer months.
- Members have **more consistent usage** year-round, peaking during weekday commute times (8 AM, 12 PM, 5 PM).

### 🌤 Seasonal Trends
- Summer months see the **highest ridership**, especially among casual riders.
- July (casual) and August (members) were peak months.

### 📍 Station & Bike Preferences
- Top stations are similar across segments but ranked differently.
- **Classic bikes** are most used; **docked bikes** are only used by casual riders.

---

## 📌 Insights

1. Casual riders follow **leisure/tourist patterns**, while members align with **commuter behavior**.
2. A subset of casual riders mirrors member behaviour — these are prime targets for conversion.
3. Weekends and summer afternoons offer major opportunities for seasonal campaigns.

---

## 💡 Recommendations

### 🧑‍💼 Target: Regular Casual Riders (Weekday users)
- Market cost savings of memberships vs. day passes
- Email personalised usage stats showing how much they could save
- Incentivise referrals and promote during weekday peaks (8 AM, 12 PM, 5 PM)

### 🧳 Target: Leisure/Tourist Riders (Weekend/Summer users)
- Create summer-only membership options or weekend passes
- Use on-site ads at popular stations/tourist spots
- Introduce points-based reward systems for long rides

---

## ⚠️ Limitations

- Only one year of data analysed (April 2022–March 2023)
- No demographic data (age, gender, income)
- Station name inconsistencies affected mapping and distance calculations

---

## 🔮 Future Analysis

In a future version, I plan to include:

- **Station Analysis**: Peak usage times and logistics planning
- **Bike Type Analysis**: Usage trends for classic vs. electric
- **Route/Distance Analysis**: Identify commuting corridors and tourist loops

---

## 📁 Files & Assets

- `cyclistic_analysis_notebook.ipynb`: Jupyter Notebook version of the project (downloaded from Kaggle)
- `README.md`: This project overview
- Tableau visual slide deck: [View here](https://public.tableau.com/views/Cyclistic-BikeShareCaseStudy_16966064333810/CyclisticBikeShare)

---

> 📌 _This case study was completed as part of the Google Data Analytics Capstone._  
> _All brand names used are fictional._

