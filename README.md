# Syria DryHeat Forecast

Machine learning for one-month-ahead heat and drought early warning in Syria.

## Overview
Syria faces recurring droughts and extreme heat that threaten agriculture and water supply, yet local decision-makers have no early warning. This project builds a machine learning model that predicts whether the next month will be **high-risk (hot and dry)** in six Syrian cities: Damascus, Aleppo, Deir ez-Zor, Al-Hasakah, Latakia and Daraa.

It extends our earlier hackathon project, *Syria DryHeat Monitor*, which analysed past trends (2000-2025), by adding a forecasting model.

## Approach
- **Data:** NASA POWER daily data (temperature, rainfall, humidity, wind, soil moisture, solar radiation, pressure).
- **Features:** lagged rainfall, number of very hot days, longest dry spell, anomaly versus the normal for the same month, and more.
- **Models:** a historical-average baseline compared with Logistic Regression, Random Forest and XGBoost, using a chronological train/test split.
- **Deployment:** a dashboard page where users select a city and see next month's risk.

## SDGs
SDG 13 (Climate Action), SDG 2 (Zero Hunger), SDG 6 (Clean Water and Sanitation).

## Files
- [Idea_Proposal.pdf](Idea_Proposal.pdf): project idea, SDG relevance and literature examples.

## Team (Group 6)
- Shilan Khalil
- Ahmad Al-Kharrat
- Eman Aboud
- Rama Albasha
- MHD Moumen Owdeh

## Programme
Frontier Tech Leaders Programme, AI for Climate (FTL Syria).
