# Support Vector Machine (SVM) Classification

This Jupyter Notebook (`svm.ipynb`) demonstrates SVM classification using the Breast Cancer dataset and synthetic data, including model training, hyperparameter tuning, cross-validation, and decision boundary visualization.

## Contents

- **Data Loading:**  
  Loads the Breast Cancer dataset from scikit-learn.

- **Preprocessing:**  
  Standardizes features using `StandardScaler`.

- **Model Training & Evaluation:**  
  - Splits data into training and test sets.
  - Trains SVM with linear and RBF kernels.
  - Prints accuracy scores for both kernels.

- **Decision Boundary Visualization:**  
  - Generates a synthetic 2D dataset.
  - Trains an RBF SVM on the synthetic data.
  - Plots the decision boundary using matplotlib.

- **Hyperparameter Tuning:**  
  - Uses `GridSearchCV` to find the best `C` and `gamma` for RBF SVM.
  - Prints best parameters and cross-validation score.

- **Cross-Validation:**  
  - Evaluates RBF SVM using 5-fold cross-validation on the full dataset.
  - Prints individual fold scores and mean score.

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Open `svm.ipynb` in Jupyter Notebook or VS Code.
2. Run each cell step by step to load data, train models, tune hyperparameters, and visualize results.

## Notes

- The notebook demonstrates both real and synthetic data usage for SVM.
- Decision boundary plots are shown for 2D synthetic data.
- Hyperparameter tuning and cross-validation help