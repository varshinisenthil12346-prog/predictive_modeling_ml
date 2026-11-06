# predictive_modeling_ml
# Predictive Modeling Using Machine Learning

## Overview
This project builds machine learning models to predict whether a tumor is malignant or benign using the Breast Cancer Wisconsin dataset (569 samples, 30 features). It covers supervised learning, model training, and model evaluation.

## Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

## Workflow
1. Loaded the dataset and checked for missing values and class balance
2. Split the data into training (80%) and testing (20%) sets
3. Scaled features using StandardScaler
4. Trained three models:
   - Logistic Regression
   - Decision Tree
   - Random Forest
5. Evaluated models using Accuracy, Precision, Recall, F1-score, ROC AUC and 5-fold cross-validation
6. Visualized performance with confusion matrices, ROC curves, a model comparison chart and feature importance

## Results
- Best model accuracy: **98.25%**
- Full comparison of all models is saved in `model_results.csv`
- Most important features: worst area, worst concave points (from Random Forest feature importance)

## Files
- `Untitled1.ipynb` - Complete code and outputs
- `model_results.csv` - Model comparison table
- `confusion_matrices.png` - Confusion matrix of each model
- `roc_curves.png` - ROC curves with AUC scores
- `model_comparison.png` - Accuracy, precision, recall and F1 comparison
- `feature_importance.png` - Top 10 important features

## Conclusion
All three models predicted tumor type with high accuracy. Ensemble and linear models performed best, showing that supervised learning works well for medical classification problems.
