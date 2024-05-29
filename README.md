# Optimizing Neural Network Architectures for Wine Quality Prediction

## Overview

This project aims to develop and optimize various neural network architectures to predict the quality of wine based on its chemical properties. By experimenting with different network configurations, the goal is to identify the most accurate model for wine quality classification, ultimately achieving a high level of predictive accuracy.

## Objective

The main objective is to leverage deep learning techniques to classify wine quality accurately and explore different neural network architectures to find the best model for this task.

## Steps Involved

1. **Data Loading and Preprocessing**
   - Load the wine quality dataset.
   - Separate features and target variable.
   - Map target variable for one-hot encoding.

2. **Exploratory Data Analysis (EDA)**
   - Plot distributions of each chemical property.
   - Analyze the distribution of wine quality.

3. **Model Development**
   - Define and compile various neural network models with different architectures.
   - Train each model on the dataset.
   - Evaluate the performance of each model.

4. **Model Evaluation**
   - Make predictions with each model.
   - Compare predictions with actual values.
   - Calculate accuracy and generate classification reports.

5. **Model Optimization**
   - Experiment with different numbers of hidden layers and neurons.
   - Identify the architecture that provides the best accuracy.

6. **Visualization**
   - Plot training loss and accuracy over epochs for the best-performing model.

## Dataset

The dataset used in this project is the Wine Quality dataset, which contains various chemical properties of red wine samples, along with their quality ratings.

## Conclusion

The project successfully developed and optimized multiple neural network models for predicting wine quality. Through systematic experimentation, the final model with four hidden layers and optimized neuron counts achieved an impressive accuracy of 95%. This demonstrates the potential of neural networks in handling complex classification tasks and highlights the importance of model architecture optimization in achieving high predictive performance.
