# CS 6220 - Homework Submissions

This repository contains Jupyter notebooks for CS 6220 homework assignments.

## Setup

1. Clone this repository.
2. Create a virtual environment:
   ```
   python3 -m venv venv
   source venv/bin/activate   
   ```
3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Launch Jupyter Lab:
   ```
   jupyter lab
   ```
5. Open the relevant notebook (e.g. `homework_1.ipynb`) and run the cells in order.

## Structure

- `homework_1.ipynb` — HW1: environment setup + scikit-learn pipeline on the Iris dataset
- `requirements.txt` — Python dependencies

## Homework 1

Builds a scikit-learn Pipeline (StandardScaler + LogisticRegression) to classify Iris flower species. Splits data 80/20 train/test, reports training/testing time and accuracy.
