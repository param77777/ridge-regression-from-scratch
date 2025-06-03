# Real Estate Price Prediction using Ridge Regression

This project implements a linear regression model with L2 regularization (Ridge Regression) from scratch using NumPy. The dataset is based on real estate data and predicts house price per unit area based on several features.

## 📁 Dataset

The dataset contains the following features:

- `X1`: Transaction date  
- `X2`: House age  
- `X3`: Distance to the nearest MRT station  
- `X4`: Number of convenience stores  
- `X5`: Latitude  
- `X6`: Longitude  
- `Y`: House price per unit area (target)

## 🧠 Model

The model uses:

- **Gradient Descent** optimization  
- **L2 Regularization** (Ridge)
- **Feature Scaling** (Normalization)

## 📊 Evaluation

- **Cost Function Visualization** over iterations
- **Effect of Regularization (λ)** on cost
- **R² Score**
- **Predicted vs Actual Plot**

## 📦 Requirements

```bash
pip install numpy pandas matplotlib scikit-learn
