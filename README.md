# Phoneme-Recognition-and-its-Applications-in-Computer-Aided-Pronunciation-Training

This repository contains the implementation of various deep learning models for phoneme recognition, with applications to Computer-Aided Pronunciation Training (CAPT). Phoneme recognition is an essential task in speech and language technologies, playing a significant role in tasks like speech recognition, speaker identification, and pronunciation training.

# Repository Structure
The repository is structured as follows:

**Code:** This directory contains the main CAPT application and audio files for testing.<br>
**Models:** This is where all model-related notebooks are stored. The models we experimented with include DNN, RNN, CNN+RNN and the more advanced Wav2Vec2.<br>
**Performance Analysis:** Contains notebooks for analyzing and comparing the training and testing performance of the implemented models.<br>
**Preprocessing:** Contains scripts for preprocessing the TIMIT dataset used in training the models.<br>

# Code
CAPT.ipynb: This is the main notebook for the CAPT application. It utilizes the trained models to provide real-time pronunciation training.<br>
Lion.wav and Test-1.wav: These are sample audio files which you can use to test the CAPT application.
Models<br>
timit-dnn-phoneme-final.ipynb: This notebook contains the implementation of a Deep Neural Network (DNN) model for phoneme recognition.<br>
timit-rnn-final.ipynb: This notebook contains the implementation of a Recurrent Neural Network (RNN) model for phoneme recognition.<br>
timit-cnn-rnn-final.ipynb: This notebook includes the implementation of a combined Convolutional and Recurrent Neural Network (CNN+RNN) model for phoneme recognition.<br>
wav2vec2-phoneme-timit-analysis.ipynb: This notebook contains the application of Facebook's Wav2Vec2 model for phoneme recognition.<br>

# Performance Analysis
CompareTraining-DNN-RNN-CNN+RNN.ipynb: This notebook compares the training performance of the DNN, RNN and CNN+RNN models.<br>
CompareTesting_DNN_RNN_CNN+RNN_Wav2Vec2.ipynb: This notebook compares the testing performance of all models including the Wav2Vec2.<br>

# Preprocessing
preprocessing-timit.ipynb: This notebook contains all the preprocessing steps performed on the TIMIT corpus before training the models.

# Getting Started
To get started with this project:<br>

Clone the repository.<br>
Run the preprocessing-timit.ipynb notebook to preprocess your data.<br>
Choose a model notebook to run. Ensure you have the necessary dependencies installed.<br>
Once the model is trained, you can use the CAPT.ipynb notebook for real-time pronunciation training.<br>
