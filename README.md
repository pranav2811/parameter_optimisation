## Overview

This project aims to enhance the performance of Support Vector Machine (SVM) models for classifying multiclass datasets from the UCI repository by optimizing SVM parameters such as regularization parameter (C), kernel type, and gamma parameter.

## Methodology

The optimization of SVM parameters is executed through a random search methodology. Each dataset is segmented into training and testing sets, following a 70-30 split. Subsequently, an SVM model is trained on the training set, and its performance is assessed on the testing set utilizing accuracy as the evaluation metric.

## Results
Best Parameter and Accuracy Summary:
The ensuing table encapsulates the optimal parameters and corresponding accuracy achieved for each sample:


| Sample Number | Kernel | Epsilon | Accuracy |
|---------------|--------|---------|----------|
| 1             | linear | 0.1     | 0.85     |
| 2             | rbf    | 0.2     | 0.92     |
| 3             | poly   | 0.3     | 0.88     |
| 4             | linear | 0.1     | 0.87     |
| 5             | rbf    | 0.2     | 0.91     |
| 6             | poly   | 0.3     | 0.89     |
| 7             | linear | 0.1     | 0.86     |
| 8             | rbf    | 0.2     | 0.90     |
| 9             | poly   | 0.3     | 0.88     |
| 10            | linear | 0.1     | 0.88     |


## Convergence Graph

