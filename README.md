#  Advanced Machine Learning Experiments

A curated collection of practical laboratory experiments, data preprocessing workflows, and machine learning implementations developed for the Advanced Machine Learning curriculum.

---

##  Overview

This repository documents weekly practical lab experiments focusing on classical advanced machine learning, statistical modeling, algorithmic optimization, and data preprocessing pipelines. Each experiment is self-contained with end-to-end data manipulation, model training, and performance evaluation.

---

##  Experiments Index

| Exp # | Experiment Title | Notebook | Key Concepts & Techniques | Metrics / Evaluation | Status |
| :---: | :--- | :---: | :--- | :--- | :---: |
| **01** | Data Wrangling & Preprocessing | [`aml_exp1_data_wrangling.ipynb`](./aml_exp1_data_wrangling.ipynb) | Missing value imputation, standard scaling, categorical encoding, EDA | Data distributions, skewness analysis | ✅ Completed |
| **02** | Linear Regression & Iris Classification | [`exp2_linear_regression_iris_classification.ipynb`](./exp2_linear_regression_iris_classification.ipynb) | Ordinary Least Squares, hyper-plane fitting, feature mapping | MSE, RMSE, $R^2$ Score | ✅ Completed |
| **03** | Decision Tree Classifier (ID3) | [`exp_3_decision_tree_ID3.ipynb`](./exp_3_decision_tree_ID3.ipynb) | Information Gain, Shannon Entropy, recursive node splitting, tree pruning | Accuracy, Confusion Matrix | ✅ Completed |
| **04** | Decision Tree Mushroom Classification | [`exp_4_decision-tree_mushroom-classification.ipynb`](./exp_4_decision-tree_mushroom-classification.ipynb) | Categorical feature encoding, Gini Impurity/Entropy, binary decision trees | Precision, Recall, Classification Report | ✅ Completed |

*(New experiments will be added as lab assignments are completed)*

---

##  Repository Structure

```text
advanced-machine-learning-experiments/
│
├── .gitignore
├── README.md
├── aml_exp1_data_wrangling.ipynb                          # Exp 1: Data Preprocessing & Manipulation
├── exp2_linear_regression_iris_classification.ipynb        # Exp 2: Linear Regression & Classification
├── exp_3_decision_tree_ID3.ipynb                          # Exp 3: Decision Tree via ID3 Algorithm
└── exp_4_decision-tree_mushroom-classification.ipynb      # Exp 4: Decision Tree on Mushroom Dataset
