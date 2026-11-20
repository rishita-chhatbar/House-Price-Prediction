# House Price Prediction

A Machine Learning project built with Python to predict residential property prices based on key housing features.

## Overview
This project analyzes property attributes to estimate house prices using regression modeling. It includes data exploration, model training in a Jupyter Notebook, and a serialized trained model ready for inference.

## Dataset Features
The model is trained on `House_preicecsv.csv` using the following features:
- **area**: Total area of the property (in sq. ft.)
- **bedrooms**: Number of bedrooms
- **bathrooms**: Number of bathrooms
- **age**: Age of the property (in years)
- **location_score**: Location quality rating
- **price**: Target variable (house price)

## Project Structure
```text
House-Price-Prediction/
├── house_price_prediction.ipynb   # Data preprocessing, EDA, and model training
├── House_preicecsv.csv            # Dataset used for training and evaluation
├── house_price_model.pkl          # Saved trained ML model
└── README.md                      # Project documentation
