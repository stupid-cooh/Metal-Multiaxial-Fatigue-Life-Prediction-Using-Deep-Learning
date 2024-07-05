# Metal-Multiaxial-Fatigue-Life-Prediction-Using-Deep-Learning
This repository contains code for predicting multiaxial fatigue life of metals using deep learning models (CNN, LSTM, and GRU) combined with fully connected layers. It processes a dataset published on Materials Cloud, utilizing high-quality data to train and evaluate the models effectively. The main function of the code is to predict fatigue life by combining time-series loading paths and material mechanical properties.This code corresponds to the technical validation of a paper we are currently submitting: 
Chen, S., Bai, Y., Zhou, X. & Yang, A. A Deep Learning Dataset for Metal Multiaxial Fatigue Life Prediction. Scientific Data. (Submitting)
# Dataset
The dataset "A deep learning dataset for metal multiaxial fatigue life prediction" used in this project is publicly available on Materials Cloud (https://doi.org/10.24435/materialscloud:wt-9822.) and includes detailed information on various metallic materials and their corresponding loading paths. The dataset comprises two folders containing stress-controlled and strain-controlled CSV files, respectively, as well as a summary CSV file and an Excel file with specific information about the materials.
# Models
The following models are implemented and included in this repository:

CNN: Extracts spatial features from the loading path data.
LSTM: Captures temporal dependencies within the loading paths.
GRU: An alternative to LSTM, offering similar capabilities with a different architecture.
Fully Connected Layers: Combine the outputs from the above models to predict fatigue life.

# Usage: 
After downloading from Materials Cloud, replace the file paths in the code with the correct locations. The code can then be run directly. Note that you will need to manually install any packages not already installed during the import step.
