# Task-5Decision-Tree-and-Random-forest
# 🌳 Decision Trees & Random Forests — Heart Disease Classification

## 🎯 Objective
Build and compare **Decision Tree** and **Random Forest** models to predict heart disease presence using the Heart Disease dataset.

---

## 📘 Steps Performed
1. **Data Loading & Preparation**
   - Loaded the dataset (`heart.csv`) and explored basic statistics.
   - Split data into training and testing sets.

2. **Decision Tree Model**
   - Trained a Decision Tree Classifier.
   - Visualized the tree using `plot_tree` and Graphviz.
   - Controlled overfitting using parameters like `max_depth`.

3. **Random Forest Model**
   - Trained a Random Forest Classifier with 100 trees.
   - Compared performance with the Decision Tree model.

4. **Model Evaluation**
   - Computed accuracy on train and test sets.
   - Evaluated feature importance to understand key predictors.
   - Used 5-fold cross-validation for robustness.

---

## 📊 Results Summary

| Model | Train Accuracy | Test Accuracy | Cross-Validation Mean |
|-------|----------------|----------------|-----------------------|
| Decision Tree (Full) | 1.00 | 0.77 | - |
| Decision Tree (Depth=4) | 0.84 | 0.81 | - |
| Random Forest | 1.00 | 0.85 | 0.84 |

---

## 🔍 Key Insights
- Decision Trees tend to **overfit** if depth is unrestricted.  
- Random Forests improve performance by combining multiple trees.  
- **Feature Importance** highlights the most influential attributes.

---

## 🧰 Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `graphviz`

---
