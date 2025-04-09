## Algorithms Steps
- Import necessary libraries
- Load dataset
- Apply SMOTE method
- Split data into training and testing sets
- GAPNet
- Train model
- Evaluate models
- Plotting results graphs
  
## Data
Classification was performed on apple, grape, potato plant leaves. 
The experiments were first performed separately on each plant, then three plant leaves were combined and studied on 11 classes. 
In order to eliminate data imbalance between classes within the data sets, data augmentation was performed with the SMOTE method. 

3 different datasets were used. 
The datasets are publicly available and can be accessed from the links below.
Mohanty S., 2016, Plant Village Dataset https://github.com/spMohanty/PlantVillage-Dataset/tree/master/raw/color
Bhattarai, S., 2019, New Plant disease Dataset, https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset/data
Christine Kaeser-Chen, 2020, Plant Pathology https://www.kaggle.com/competitions/plant-pathology-2020-fgvc7/data  

Plant Village data sets and data numbers used for Leaf Disease Classification are given in the table below.
![Data Sets](https://github.com/user-attachments/assets/2c3a5567-ff3c-4860-83fa-55fcf14c5f1c)

## Environment
All experiments in this study were conducted using the Google Colab environment. A100 GPU was used.

## Code
A lightweight SqueezeNet model, GAPNet, is proposed for Grape, Apple and Potato leaf disease classification. Pre-trained convolutional neural networks VGG16, ResNet50, SqueezeNet, Xception, ShuffleNet, DenseNet121 and MobileNetV2 are used to compare model performance.

## Requirements
- Python 3.x
- numpy
- pandas
- scikit-learn
- keras
- tensorflow
  
## Implementation Language
Python

## Libraries/Packages
List the libraries and their versions (scikit-learn, TensorFlow, Keras, pandas, numpy, matplotlib)


