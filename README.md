# Mango Varieties Classification using Random Forest Classifier

This project is focused on classifying different varieties of mangoes based on their images using a Random Forest Classifier. The dataset contains images of various mango varieties, which will be used to train a machine learning model that can predict the variety of a mango given its image.

## Table of Contents

1. [Dataset](#dataset)
2. [Objective](#objective)
3. [Requirements](#requirements)
4. [Project Structure](#project-structure)
5. [Steps to Run the Project](#steps-to-run-the-project)
   1. [Data Preprocessing](#1-data-preprocessing)
   2. [Model Training](#2-model-training)
   3. [Model Evaluation](#3-model-evaluation)
   4. [Visualizing Feature Importances (Optional)](#4-visualizing-feature-importances-optional)
6. [Results](#results)
7. [Conclusion](#conclusion)
8. [License](#license)

## Dataset

The dataset used in this project can be accessed via Kaggle:

- [Mango Varieties Classification Dataset](https://www.kaggle.com/datasets/saurabhshahane/mango-varieties-classification)

The dataset includes images for several mango varieties, which will be used for training the model.

## Objective

The primary goal is to build a Random Forest Classifier model that can:

- Classify mangoes into various varieties based on their images.
- Perform image preprocessing, including resizing and normalization.
- Improve model performance through hyperparameter tuning using RandomizedSearchCV.

## Requirements

To run the code and replicate the results, you will need the following Python libraries:

- `numpy` – for numerical operations
- `pandas` – for data manipulation
- `matplotlib` – for visualizations (if desired)
- `scikit-learn` – for machine learning algorithms and model evaluation
- `PIL` (Pillow) – for image processing
- `time` – to measure execution times

You can install the necessary dependencies using `pip`:

```bash
pip install numpy pandas matplotlib scikit-learn Pillow
```
