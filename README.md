# sle-proteomics-indian-cohort
Machine learning pipeline and multi-omics analysis for distinguishing SLE flare from remission.

# SLE Flare vs. Remission: Machine Learning Pipeline

This repository contains the Python code used for the machine learning and statistical analyses in our manuscript:
**"Integrative Plasma Proteomics and Myeloid-Interferon Profiling Reveal an AI-Validated Vascular-Endothelial Stress Signature Distinguishing SLE Flare from Remission in an Indian Cohort"**

## Files Included
* `sle_ml_master_pipeline.py`: The master script that executes the Random Forest classifier, Leave-One-Out Cross-Validation (LOOCV), permutation testing, and generates all SHAP, ROC, and PCA visualizations.

## How to Run
The script requires Python 3.8+ and the following libraries:
`pandas`, `numpy`, `scikit-learn`, `scipy`, `matplotlib`, `seaborn`, `shap`.

To ensure reproducibility, the script includes a synthetic fallback dataset that mirrors the statistical properties of the 5-marker biosignature (COL18A1, HYOU1, IGHG4, FLNA, SH3BGRL3). Reviewers can run the script directly to generate the exact performance metrics and figures described in the manuscript.
