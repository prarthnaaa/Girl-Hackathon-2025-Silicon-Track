# AI-Based Combinational Logic Depth Prediction

## Overview

This repository contains the implementation of an AI model designed to predict the combinational logic depth of signals in RTL designs. The project was developed as part of the **Girl Hackathon 2025 - Silicon Track**.

## Features

- **Dataset Handling**: Includes structured RTL datasets with synthesis reports.
- **Machine Learning Model**: Uses Random Forest Regression for accurate predictions.
- **Performance Evaluation**: Implements MSE, R-squared score, and visualization techniques.
- **Graphical Representations**: Includes feature importance plots and prediction visualizations.

## Installation

### Clone the repository
```sh
git clone https://github.com/prarthnaaa/Girl-Hackathon-2025-Silicon-Track.git
cd Girl-Hackathon-2025-Silicon-Track
```

### Create a virtual environment (Recommended)
```sh
python -m venv env
source env/bin/activate   # On macOS/Linux
env\Scripts\activate      # On Windows
```

### Install dependencies
```sh
pip install -r requirements.txt
```

## Running the Code

1. **Ensure the dataset (`dataset.csv`) is in the repository directory.**
2. **Run the script to train and test the model:**
   ```sh
   python logic_depth_prediction.py
   ```
3. **Output includes MSE, R-squared score, predicted depth, and graphical analysis.**

## Graphical Representations

- **Feature Importance Plot**: Displays the significance of each feature.
- **Actual vs. Predicted Depth Scatter Plot**: Visualizes model accuracy.

## Submission Link

For submission details, refer to the Google Doc: [Submission Document](https://docs.google.com/document/d/1LB9UDRpp2txsYF4Q8oOElr6PgiyxL-ImpU9l8aiB69o/edit?tab=t.0)