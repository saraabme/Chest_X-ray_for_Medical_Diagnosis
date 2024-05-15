# Chest X-rays for Medical Diagnosis with CNN

## AI for Medicine Course by Deeplearning.ai

This repository hosts the Python script developed for the AI for Medicine Course by Deeplearning.ai. The script focuses on analyzing chest X-rays to predict conditions such as pneumonia and COVID19 using computer vision techniques and deep learning models.

Computer Vision (CV) has a lot of applications in medical diagnosis:
 - Dermatology
 - Ophthakmology
 - Histopathology.

X-rays images are critical for the detection of lung cancer, pneumenia ... In this notebook you will learn:
 - Data pre-processing 
 - Preprocess images properly for the train, validation and test sets.
 - Set-up a pre-trained neural network to make disease predictions on chest X-rays.

 In this notebook you will work with chest X-ray images taken from the public [ChestX-ray8 dataset](https://arxiv.org/abs/1705.02315). 

The ChestX-ray8 dataset contains 108,948 frontal-view X-ray images of 32,717 unique patients with the text-mined fourteen disease image labels (where each image can have multiple labels), mined from the associated radiological reports using natural language processing. 


## Project Overview

The script demonstrates the process of loading, preprocessing, and predicting medical conditions from chest X-ray images using a pre-trained model. The data utilized is the ChestX-ray8 dataset, which is publicly available.


## Key Features

- Preprocessing X-ray images for neural network input.
- Utilizing a pre-trained DenseNet121 model for disease prediction.
- Handling class imbalance in medical image datasets.


## Prerequisites

We'll make use of the following packages:
 - `numpy` and `pandas` is what we'll use to manipulate our data
 - `matplotlib.pyplot` and `seaborn` will be used to produce plots for visualization
 - `util` will provide the locally defined utility functions that have been provided for this assignment
 - We will also use several modules from the `keras` framework for building deep learning models.


## Installation

Clone the repository and install the necessary Python libraries:

```bash
pip install numpy pandas matplotlib seaborn keras sklearn
```


## Data

The project uses the ChestX-ray8 dataset. Ensure you have downloaded and properly placed this dataset in the data/ directory, with appropriate subdirectories for training, and testing for the follwing classes: COVID19, Pneumonia, and Normal.


## Acknowledgments

Deeplearning.ai for the course and educational content.
Authors and maintainers of the ChestX-ray8 dataset.
