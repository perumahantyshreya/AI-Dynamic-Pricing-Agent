# AI-Agent Driven Disruption of Online Travel Marketplaces/Agencies

## Overview
This project develops an AI-driven pricing system for hotel bookings that combines machine learning and rule-based logic to recommend optimal room prices dynamically.

## Problem
Traditional OTA platforms use centralized pricing models with limited transparency and host control.

## Solution
A hybrid pricing engine:
- **ANN Model** for price prediction
- **Rule-based system** for contextual adjustments
- Final price = 60% ML + 40% rule-based

## Dataset
- OTA booking dataset (5,000 rows)
- Features: occupancy, season, competitor pricing, booking pace

## Results
- R² Score: ~0.92  
- RMSE: ₹362  
- High generalization with minimal overfitting  

## Tech Stack
- Python  
- Scikit-learn  
- Neural Networks (MLP)  

## Key Insight
Competitor pricing contributes ~82% to price prediction.

## Future Work
- Real-time API integration  
- Reinforcement learning pricing  
- Explainable AI (SHAP/LIME)
