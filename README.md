# AIML_8_FailureSensorPredictor_byte

## Overview
This repository contains the solution for **Task 8: The "Failure" Sensor Predictor (Predictive Maintenance System)** under the Arithmatrix Virtual Internship Program (AVIP 2026). The objective is to process industrial IoT sensor telemetry and forecast equipment failure before it occurs, minimizing false alarms and missed failures using strict precision and recall metrics.

## Features
- **Rolling Window Feature Engineering**: Extracted moving averages and standard deviations over time-series telemetry blocks to capture gradual degradation patterns.
- **Predictive Modeling**: Trained a machine learning classifier to predict failures ahead of time.
- **Strict Evaluation**: Focused heavily on Precision and Recall curves to avoid unnecessary downtime and catastrophic breakdowns.

## Deliverables Included
- Jupyter Notebook / Python Script for data preprocessing and feature engineering.
- Trained model artifact (`predictive_maintenance_model.pkl`).
- Evaluation metric charts (`evaluation_metrics.png`).

## How to Run Inference
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
