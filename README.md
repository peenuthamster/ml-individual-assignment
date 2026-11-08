# Machine Learning Individual Assignment

Workspace for the CSC61304 Machine Learning and Intelligent Systems individual assignment.

## Status

Dataset and models are selected. The notebook (EDA, preprocessing, model training, tuning and evaluation) is complete. The report is in progress.

## Dataset

[Richter's Predictor: Modeling Earthquake Damage](https://www.drivendata.org/competitions/57/nepal-earthquake/): structured building data from the 2015 Nepal earthquake. The task is to predict a building's damage grade (1 to 3).

## Models

- Logistic Regression
- Random Forest
- CatBoost

## Contents

- `notebook/earthquake_damage_prediction.ipynb`: full analysis and modelling
- `notebook/figures/`: plots used in the report
- `notebook/outputs/`: result tables

## Running the notebook

Place `earthquake_train_combined.csv` in the project root (one folder above the notebook), or set the `DATA_DIR` environment variable to its folder. Then run the notebook with Python 3 and `pandas`, `scikit-learn`, `catboost`, `matplotlib`, `seaborn`, `scipy` and `joblib` installed. A full run takes about 30 minutes.

The assessment guidelines and the downloaded datasets are kept locally and are not included in this repository. Obtain the dataset from its original source and follow the applicable terms of use.
