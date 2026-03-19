# Influencer Marketing Effectiveness on Social Media

A data analysis research project investigating whether commonly used influencer marketing metrics (reach and engagement) can predict actual product sales.

## Overview
Brands typically evaluate influencer campaigns using reach and engagement. This study tests whether these metrics have real predictive power over actual sales outcomes using real campaign-level data.

## Key Findings
- Reach and engagement explain minimal variation in actual product sales (R² ≈ 0.00 on ROI dataset)
- Merged campaign dataset achieved R² ≈ 0.70 using revenue-based feature engineering
- Micro and Nano influencers statistically outperform Macro and Mega influencers:
  - Conversion Rate: p = 0.001
  - ROI: p = 0.0000006
  - Revenue per Follower: p = 0.0017
  - Audience Match: p = 0.036

## Tech Stack
- Python, Pandas, NumPy
- Statsmodels, Scipy
- Matplotlib, Seaborn
- Google Colab

## Analyses Included
- OLS Regression (baseline and enhanced models)
- Log transformation for skewed distributions
- Feature engineering (Conversion Rate, Revenue per Follower, ROI)
- t-tests for influencer tier comparison (Micro vs Macro)

## Datasets
See `data/links.txt` for all dataset sources (Kaggle).

## Report
Full research report included as `report.pdf`
