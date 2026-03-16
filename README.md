# Critical Analysis of Machine Learning and Deep Learning Models for Predicting Medical Equipment Demand in Hospitals

## Overview
This repository presents my research thesis on forecasting medical equipment demand in hospitals using statistical, machine learning, and deep learning models. The project investigates whether advanced predictive approaches can improve forecasting accuracy over traditional time-series methods and support more effective healthcare resource planning.
The aim of this research is to evaluate and compare forecasting approaches for predicting medical equipment demand in hospital environments, with a focus on improving planning, allocation, and operational efficiency.

## Research Question
To what extent can advanced machine learning and deep learning models such as XGBoost, LSTM, GRU, and N-BEATS outperform traditional statistical approaches such as SARIMAX in forecasting medical equipment demand, and how can these improvements support healthcare resource planning and operational efficiency?

## Objectives
- Analyse medical equipment demand data to identify temporal and seasonal patterns
- Develop and compare statistical, machine learning, and deep learning forecasting models
- Evaluate model performance using standard forecasting metrics
- Improve model transparency through explainability techniques

## Methodology
The project follows an end-to-end forecasting workflow including data collection, preprocessing, feature engineering, model development, evaluation and interpretation. Multiple modelling approaches are implemented and assessed within a common experimental framework to enable fair comparison.

## Models Evaluated
- SARIMAX
- XGBoost
- LSTM
- GRU
- N-BEATS

## Explainability
To improve transparency and trust in model predictions,explainability techniques such as **SHAP** are considered as part of the analytical framework.

## Evaluation Metrics
The models are evaluated using the following performance metrics:
- RMSE
- MAE
- R² Score

## Repository Contents
- `x23377755 - Raghul Sureshbabu - Research Thesis Report.pdf` — full thesis report
- `x23377755 - Raghul Sureshbabu - Research code artefact.ipynb` — implementation notebook
- `x23377755 - Raghul Sureshbabu - Research Config Manual.pdf` — configuration and setup manual

## Dataset
This research uses the CMS Medicare Durable Medical Equipment, Devices & Supplies by Geography and Service public dataset, compiled from annual CMS utilisation files covering 2014–2023. The data were cleaned, schema-aligned across years and aggregated at the State–HCPCS–Year level for forecasting analysis.

## Author
**Raghul Sureshbabu**
