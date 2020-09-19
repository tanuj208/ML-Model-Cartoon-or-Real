# ML-Model-Cartoon-or-Real

## Introduction
This contains a Machine Learning Model to decide whether a given image is an image of a cartoon or of a real person.

## Pipeline
Dataset of various picture sizes is taken and split into two parts - 80% for training & rest 20% for testing.

Images are flattened and then reduced to 80 dimensions using Kernel Principle Component Analysis with 3 degree rbf kernel. Then, a multi layer perceptron classifier is used with 2 hidden layers & adam optimization.

## Results
Obtained accuracy on testing data is 97.18% with a precision score of 1.0, a recall score of 0.95 & an F1 score of 0.97.

## Running the code
Open the notebook `model.ipynb` & run all the cells in order. A brief report is also present with the name `report.pdf`.
