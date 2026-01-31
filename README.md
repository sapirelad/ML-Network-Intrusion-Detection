# ML-Based Network Intrusion Detection

This repository contains the final project for the course *Machine Learning for Cyber Systems*.

## Project Goal
The goal of this project is to analyze and evaluate machine learning approaches for **network intrusion detection**, with an emphasis on:
- data characteristics and limitations,
- model evaluation under class imbalance,
- robustness and generalization across datasets.

## Datasets
- **CICIDS2017** – realistic network traffic with labeled attack scenarios.
- **UNSW-NB15** – modern intrusion dataset with different traffic distributions.

> Due to size and license constraints, datasets are **not included** in this repository.

## Methodology
The project includes:
- Exploratory Data Analysis (EDA)
- Supervised baselines (Dummy, Logistic Regression, Random Forest)
- Unsupervised learning (Spectral Clustering)
- Graph-based semi-supervised learning (Label Propagation / Label Spreading)
- Cross-dataset evaluation (CIC → UNSW, UNSW → CIC)
- Threshold tuning under dataset shift

## Main Findings
- Strong performance within the same dataset does **not** transfer across datasets.
- Cross-dataset evaluation reveals significant **dataset shift**.
- Graph-based semi-supervised methods show promise when labeled data is limited.
- Threshold tuning can partially mitigate recall degradation under dataset shift.

## Repository Structure
- `ML_For_Cyber-5.ipynb` – full analysis, experiments, and results.

## Author
Sapir Elad
