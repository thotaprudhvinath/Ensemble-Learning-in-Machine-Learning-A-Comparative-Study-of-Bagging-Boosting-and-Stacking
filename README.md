# Ensemble Learning: Bagging, Boosting, and Stacking

This repository contains an in-depth analysis and implementation of Bagging, Boosting, and Stacking ensemble learning models. The project includes data preprocessing, model training, evaluation, and performance comparison using the Cleveland Heart Disease dataset.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Dataset](#dataset)
- [Model Implementation](#model-implementation)
- [Results](#results)
- [Usage](#usage)
- [Contributions](#contributions)
- [License](#license)

## Introduction
Ensemble learning is a technique in machine learning that combines multiple models to improve predictive performance. This project explores three ensemble methods: **Bagging**, **Boosting**, and **Stacking**.

- **Bagging** reduces variance by training models in parallel.
- **Boosting** sequentially builds models, focusing on correcting the errors made by previous models.
- **Stacking** combines the predictions of different base models using a meta-learner to optimize the final output.

This project applies these models to predict heart disease presence using medical data.

## Installation
To run this project, install the required dependencies:

```sh
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```sh

## Usage 
git clone https://github.com/your-username/ensemble-learning.git
cd ensemble-learning

python train_model.py

## License
This project is licensed under the MIT License - see the LICENSE file for details.

