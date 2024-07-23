# AdvisorySage: Predictive Analytics for Financial Advisory Services

## Overview

AdvisorySage is a machine learning project aimed at identifying potential candidates for financial advisory services among clients with unknown status. Using a combination of clustering and anomaly detection techniques, this project analyzes client data to predict which individuals are likely to benefit from advisory services but haven't yet opted in.

## Features

- Data preprocessing and exploratory data analysis
- Multiple model approaches:
  1. One-Class Classification Models:
     - One-Cluster KMeans
     - Isolation Forest
     - One-Class SVM
     - Ensembled Isolation Forest
  2. KMeans Clustering with Density-Based Selection

- Performance evaluation using F1 score
- Visualization of model results and thresholds

## Dataset

The dataset contains client information including:
- Demographic data (Age)
- Financial information (Income)
- Job Type (VP, Chief Officer, Owner)
- Tax Classification (Low, Medium, High)
- Current advisory status (Advisory, Unknown)

## Key Findings

- The Ensembled Isolation Forest model achieved the best performance in identifying potential advisory clients.
- Job Type and Income levels were strong indicators of advisory service candidacy.
- Certain clusters within each job type showed higher densities of advisory clients.

## Future Work

- Implement more sophisticated ensemble methods
- Explore deep learning approaches for feature extraction
- Develop a user interface for easy model interaction and result visualization
