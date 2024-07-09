# Drug_Potency_ML

## Introduction
Jupyter Notebooks and datasets for a machine learning pipeline that predicts the potency of drugs and druglike molecules associated with a disease. The pipeline investigates the potency of compounds targeting a SARS coronavirus 3C-like proteinase, but it can be applied to any protein or disease of choice.

## Data processing
Data for this project is pulled from the ChEMBL database. The data is processed using each compound's canonical SMILE (Simplified Molecular Input Line Entry), IC50 value (measure of drug potency), and PubChem fingerprints (chemical structure indicator) to create a dataset to be used for various regression models.

## Machine Learning
This repository contains four different regression model implementations (Random Forest Regression, XGBoost Regression, Multilayer Perceptron Regression, and a Keras Regression neural network) in order to compare performance.
