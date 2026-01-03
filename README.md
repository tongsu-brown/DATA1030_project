# DATA1030 Project
## Thin-Film Stress–Thickness Prediction with Machine Learning (DATA 1030 Final Project)

This repository contains the code and report for my DATA 1030 final project. I apply supervised machine learning to predict **stress–thickness behavior** in thin films from deposition process conditions and basic material descriptors.

Project goals:
- Train and evaluate multiple regression models (e.g., Random Forest, Gradient Boosting) to predict stress–thickness.
- Interpret model behavior using global feature importance (permutation / SHAP / built-in tree importances) and local explanations (SHAP).
- Provide a reproducible pipeline that generates the figures and results used in the final report.
- Serve as a prototype toward a universal thin-film stress modeling framework.

## Data availability
The full stress–thickness database is not publicly distributed at this time (ongoing manuscript preparation).  
Data can be shared for academic use upon request: **tong_su@brown.edu**.

## Reproducibility

### Environment
Create and activate the conda environment:
```bash
conda env create -f environment.yml
conda activate data1030
