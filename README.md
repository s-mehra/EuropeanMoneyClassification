# EuropeanMoneyClassification
This GitHub project focuses on training, validating, and testing two deep learning models implemented in the PyTorch framework for classifying Euro bills based on given images. The models included in this project are ResNet-18 and DenseNet-121, which have shown excellent performance in image classification tasks.

## Table of Contents

- Project Overview
- Dataset
- Models

## Project Overview
The objective of this project is to develop deep learning models capable of correctly classifying Euro bills based on input images. The models are implemented using the PyTorch framework, utilizing ResNet-18 and DenseNet-121 architectures. The project aims to simplify and automate the process of currency classification, reducing manual effort and increasing accuracy.

The repository includes the following components:

data/: This directory contains the Euro bill dataset used for training, validating, and testing the models as well as CSV files that include the labels for each image.

models/: This directory contains the implementation of the ResNet-18 and DenseNet-121 models for Euro bill classification.
EuropeanMoneyClassification.ipynb: A Jupyter Notebook which includes loading and preparation of data, training and validating the models, and testing and comparing the two models created.

README.md: This file provides an overview of the project, instructions, and guidelines.
## Dataset

The dataset used for training and evaluating the models was taken from IMB sample set and consists of a collection of images of Euro bills for training, evaluating and testing. The dataset also included a set of CSV files which included labels for each image in each set as well as other information about each image.

## Models

In this project, two pre-trained models were loaded and their last layer was customized and trained on the data set.

The two PyTorch deep learning models in this project are:

- ResNet-18: This model is a variant of ResNet with 18 layers. It utilizes residual connections to enable effective training of deep neural networks. The ResNet-18 model is known for its simplicity and efficiency while achieving high accuracy in image classification tasks.
- DenseNet-121: DenseNet is a densely connected convolutional neural network architecture. The DenseNet-121 model consists of a series of dense blocks, where each layer is connected to every other layer in a feed-forward manner. This connectivity pattern promotes feature reuse and enhances gradient flow, leading to improved performance.

Both models are implemented in the models/ directory. The implementation includes the model architecture, training, and evaluation procedures using the PyTorch framework.

