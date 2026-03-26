# Taming the Market: Understanding Overfitting in Decision Trees

## Project Overview
This repository contains the code and tutorial for my Machine Learning assignment. The objective of this project is to demonstrate the concept of **overfitting** in machine learning, specifically focusing on how `DecisionTreeClassifier` models behave when they are unconstrained versus when they are pruned.

To illustrate this, the project uses real-world, dynamic financial data (the Nifty 50 Index). Financial data is notoriously noisy, making it the perfect dataset to show how an unconstrained model will memorize historical noise rather than learning actual predictive trends.

## Repository Contents
* `overfitting_tutorial.ipynb`: The main Jupyter Notebook containing all the Python code to fetch data, train the models, and generate the visualizations.
* `overfitting_plot.png`: The generated plot demonstrating the divergence between training and testing accuracy (used in the tutorial document).
* `Tutorial_Document.pdf`
* `README.md`: This file.
* `LICENSE`: The license file detailing usage rights.

## Prerequisites and Installation
To run the Jupyter Notebook, you will need Python installed along with several data science libraries. 

The most important dependency is `yfinance`, which is used to fetch the dynamic dataset directly from Yahoo Finance.

You can install all required packages by running the following command in your terminal or command prompt:

```bash
pip install yfinance pandas numpy matplotlib scikit-learn
