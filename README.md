# ANN-Based Classification of Glass Identification Using MLP

## Project Overview
This project uses an Artificial Neural Network (ANN), specifically a Multi-Layer Perceptron (MLP), to classify glass samples based on their chemical composition.

## Dataset
- Dataset: UCI Glass Identification Dataset
- Total samples: 214
- Input features: 9
- Output classes: 6

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Model Architecture
- Multi-Layer Perceptron (MLP)
- ReLU activation
- Softmax output
- Stochastic Gradient Descent (SGD)
- Momentum and L2 regularization
- Early stopping

## Project Workflow
1. Dataset collection
2. Data preprocessing
3. Feature scaling
4. ANN model development
5. Model training and experiments
6. Model evaluation
7. Glass type prediction

## Results
The model is evaluated using accuracy, precision, recall, F1-score and a confusion matrix.

## How to Run
Install the required libraries:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn joblib
```

Run:

```bash
python glass_ann_project.py
```

## Dataset Source
UCI Machine Learning Repository – Glass Identification Dataset.
