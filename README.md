# Machine Learning

Collection of machine learning projects developed for coursework at the Center of Informatics (CIn), Federal University of Pernambuco (UFPE).

The repository contains Jupyter notebooks that apply and evaluate supervised learning algorithms on public datasets. Topics include classification, hyperparameter optimization, ensemble methods, and neural networks.

## Repository Structure

| Notebook                                   | Description                                                                                                                                                                               |
| ------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `Churn_Redes_Neurais.ipynb`                | Customer churn prediction for a telecommunications dataset using Multilayer Perceptron (MLP), STab, TabPFN v2 Transformer, KAN, TabKAN, Mitra, and Gradient Boosting.                     |
| `KNN-LVQ-SVM.ipynb`                        | Hyperparameter optimization and performance comparison of K-Nearest Neighbors (K-NN), Learning Vector Quantization (LVQ), and Support Vector Machine (SVM) on the Spotify Tracks dataset. |
| `Miniprojeto_1_Redes_Neurais_2025_2.ipynb` | Image classification on the CIFAR-10 dataset using Multilayer Perceptron (MLP) and Convolutional Neural Network (CNN).                                                                    |
| `projeto_1.ipynb`                          | Comparative study of Decision Tree, Naive Bayes, Logistic Regression, and K-Nearest Neighbors on the Breast Cancer Wisconsin (Diagnostic) dataset.                                        |
| `projeto_2_parte_1.ipynb`                  | Parametric analysis of K-NN, LVQ, Decision Tree, SVM, and Random Forest on the House_16H v2 dataset.                                                                                      |
| `projeto_2_parte_2.ipynb`                  | Parametric analysis of MLP, Neural Network Ensemble, Heterogeneous Stacking Ensemble, XGBoost, and LightGBM on the House_16H v2 dataset.                                                  |

## Main Topics

* Supervised learning
* Classification
* Hyperparameter optimization
* Artificial neural networks
* Ensemble learning
* Tabular data analysis
* Model evaluation and comparison

## Datasets

The notebooks use publicly available datasets, including:

* Customer Churn Telecom Services
* Spotify Tracks
* CIFAR-10
* Breast Cancer Wisconsin (Diagnostic)
* House_16H v2

Some datasets are downloaded automatically by the notebooks, while others must be provided separately.

## Requirements

The notebooks were developed in Python using Jupyter Notebook.

Common dependencies include:

* NumPy
* pandas
* scikit-learn
* matplotlib
* PyTorch
* torchvision
* XGBoost
* LightGBM

Some notebooks require additional libraries for specific models, such as TabPFN, STab, KAN, TabKAN, and Mitra.

## Usage

1. Clone the repository.
2. Install the required dependencies.
3. Download the datasets when necessary.
4. Open the desired notebook in Jupyter Notebook or JupyterLab.
5. Execute the cells in order.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
