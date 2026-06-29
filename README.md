# Titanic-Survival-RF-SVM-LR

Survival prediction for the Kaggle Titanic competition, comparing Random Forest, SVM, and Logistic Regression.

## Approach
- **Cleaning:** filled Age (median by title), Embarked (mode), Fare (median); Cabin → `HasCabin`.
- **Feature engineering:** `Title`, `FamilySize`, `IsAlone`.
- **Models:** Logistic Regression, SVM, Random Forest (compared via 5-fold cross-validation).

## Result
Best model: **Random Forest** — Kaggle public score **0.777**. Test result **0.811**.

## Usage
```bash
pip install pandas scikit-learn
