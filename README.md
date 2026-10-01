# Customer Segmentation and Predictive Analytics

Machine-learning laboratory project based on the supplied R Programming Lab Problem Statement 6.

## Problem statement

An e-commerce company wants to better understand its customers and improve marketing decisions. Using historical online retail transaction data, the project:
- preprocesses transaction data;
- engineers customer-level RFM and purchasing features;
- performs K-Means and Hierarchical Clustering;
- selects clusters using the Elbow Method;
- evaluates clustering with Silhouette Score;
- uses PCA for 2D visualization;
- profiles customer segments;
- defines a high-value customer segment;
- trains Random Forest and SVM classifiers;
- evaluates Accuracy, Precision, Recall, F1, ROC-AUC and Confusion Matrix;
- analyzes feature importance;
- creates an interactive Plotly 3D cluster visualization;
- generates segment-wise marketing recommendations.

## Dataset

UCI Machine Learning Repository — Online Retail Dataset.

The notebook downloads the dataset automatically from the UCI repository. The raw dataset is intentionally not committed to GitHub because it is large and can be reproduced by running the notebook.

## How to run

### Google Colab
1. Upload `customer_segmentation.ipynb` to Google Colab.
2. Run all cells from top to bottom.
3. The notebook installs required packages and downloads the dataset automatically.
4. Generated charts and model results appear in the notebook.

### Local Python
```bash
pip install -r requirements.txt
jupyter notebook customer_segmentation.ipynb
```

## Repository structure

```text
r_customer_segmentation_github/
├── customer_segmentation.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── outputs/
    └── .gitkeep
```

## Important note

Although the supplied document is titled as an R Programming laboratory assignment, its submission instructions explicitly require the experiment to be completed using Python in Google Colab. This repository therefore implements the requested workflow in Python.

## AI prompt supplied in the assignment

The assignment includes this prompt:

> Evaluate the given R Programming laboratory assignment using a 1–4 rubric for Real-life Application, Problem-solving Ability, Critical Reasoning, Creativity, and Alignment with Learning / Course Outcomes. Identify the estimated time required, map the relevant Course Outcomes (CO1–CO6) and Learning Outcomes (LOs), and justify the ratings based on the R Programming syllabus covering unsupervised learning, clustering, dimensionality reduction, feature engineering, predictive maintenance, supervised machine learning, model evaluation, visualization, and end-to-end data science workflows.

## Academic integrity

Review the generated analysis, interpretations and recommendations before submission and adapt them to your instructor's required format.
