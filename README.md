
# Student Depression Analysis & Prediction

A machine learning project in R exploring factors associated with
depression among students and young professionals, and building
predictive models to identify at-risk individuals.

## Overview

This project analyzes variables such as academic pressure, sleep
patterns, dietary habits, work hours, and demographic characteristics to
understand their influence on depression risk. The focus is on
**recall** as the primary evaluation metric, prioritizing the correct
identification of at-risk individuals over minimizing false positives.

## Project Structure

```         
├── analysis.Rmd               # Full analysis and modeling code
├── analysis.html              # Rendered report
├── student_depression_dataset.csv  # Dataset
└── README.md
```

## Methods

### Models Compared

-   Logistic Regression
-   Stepwise Logistic Regression 
-   K-Nearest Neighbors (KNN)
-   Naive Bayes
-   Classification Tree
-   Random Forest

### Evaluation

-   Combined Confusion Matrix
-   10-Fold Cross-Validation
-   Primary metric: **Recall** (minimizing false negatives)

## Key Findings

-   The strongest predictors of depression were **suicidal thoughts,
    academic pressure, and financial stress**
-   Sleep habits, diet, work hours, and personal background also
    contribute to depression risk
-   **Naive Bayes and Stepwise GLM** achieved the highest recall, making
    them most effective for identifying at-risk individuals

## Requirements

R packages used:

-   `corrplot`
-   `ggplot2`
-   `caret`
-   `e1071`
-   `rpart`
-   `partykit`
-   `ranger`
-   `party`
-   `MLmetrics`
-   `MASS`
-   `class`
-   `gridExtra`
-   `RColorBrewer`
