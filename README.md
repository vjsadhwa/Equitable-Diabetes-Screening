# Equitable Diabetes Risk Prediction

### Project Overview

Developed a machine learning framework to predict diabetes risk and optimize the allocation of limited healthcare screening resources while addressing demographic disparities.

### Business Objectives

- Reduce differences in diabetes detection rates across demographic groups.
- Maximize diabetes detection within a screening capacity of 1,000 appointments per 10,000 people.

### Data & Methodology

- 249,000+ survey observations from the 2015 BRFSS dataset
- Logistic Regression, LDA, Random Forest, and Neural Networks
- Random oversampling and hyperparameter tuning
- Group-specific threshold optimization
- Fairness evaluation and bootstrap confidence intervals

### Key Results

| Metric | Baseline: Top 10% | Equity Strategy |
|---|---:|---:|
| Cases detected per 10,000 | 499 | 469 |
| Largest miss-rate gap | 33.5 pp | 6.2 pp |
| Screening appointments | 1,000 | 1,000 |

The proposed strategy reduced demographic miss-rate disparities by approximately 82% while retaining 94% of baseline detections and maintaining clinic capacity on held-out test data. The five-percentage-point equity target was narrowly missed.

### Project Deliverables

- Jupyter Notebook — Data preparation, modeling, and evaluation
- Final Presentation — Business objectives, analytical findings, and recommendations
- Visualizations — Model comparisons and screening strategy tradeoffs

### Technologies

Python · scikit-learn · Machine Learning · Constrained Optimization · Responsible AI

### Limitations

This academic project uses historical, self-reported survey data. Further clinical validation would be required before real-world implementation.
