# FIFA World Cup 2026 — Match Outcome Predictor 🏆

## Overview
A machine learning project that predicts FIFA World Cup 2026 match outcomes using historical World Cup data (1930–2014). Built a Random Forest classification model and an interactive Power BI dashboard to visualize predictions and team performance metrics.

## Live Predictions
- 🏆 Predicted WC 2026 Winner: **Croatia**
- Model Accuracy: **54.49%** *(industry benchmark for soccer prediction is 55-60%)*

## Tech Stack
- **Python** — Pandas, NumPy, Scikit-learn
- **Machine Learning** — Random Forest Classifier
- **Visualization** — Power BI
- **Environment** — Google Colab

## Project Structure

## Methodology
1. **Data Collection** — Historical WC match data (1930–2014) from Kaggle
2. **Data Cleaning** — Handled missing values, unified Germany pre/post reunification
3. **Feature Engineering** — Calculated avg goals scored/conceded and WC experience per team
4. **Model Training** — Random Forest with 80/20 train-test split
5. **Tournament Simulation** — Simulated full WC 2026 bracket with real group stage draw

## Dashboard
Interactive Power BI dashboard featuring:
- Match win probability bar chart
- Team strength bubble chart (goals scored vs conceded, sized by experience)
- Full predictions table
- KPI cards (852 matches analyzed, 54.49% accuracy)

## Key Findings
- Home teams win ~58% of matches historically
- Draws are the hardest to predict (19% precision) — consistent with all soccer prediction models
- Teams with fewer than 10 WC appearances were normalized to avoid data bias

## Limitations & Future Improvements
- Model uses historical team stats only — does not account for current squad form or individual player quality
- Future improvement: integrate a live player stats API (football-data.org) to add features like recent form, injury status, and FIFA rankings

## Author
**Swastik **  
MS Data Analytics — George Mason University  
[LinkedIn](https://linkedin.com) | [GitHub](https://github.com)
