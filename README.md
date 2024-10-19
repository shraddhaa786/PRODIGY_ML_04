# PRODIGY_ML_04


# Hand Gesture Recognition Model

## Project Overview
This project focuses on building a hand gesture recognition model that can accurately identify and classify various hand gestures from image and video data. The model aims to enhance human-computer interaction and enable gesture-based control systems for a variety of applications, such as gaming and assistive technologies.

## Dataset
The dataset used for this project is from Kaggle: [Leap Gestures Dataset](https://www.kaggle.com/gti-upm/leapgestrecog). The dataset includes a variety of hand gestures, such as palm, thumb, index finger, and other distinct gestures, captured under different lighting and hand positions.

## Model Architecture
The model is a Convolutional Neural Network (CNN) built using Keras. The architecture consists of several convolutional layers, pooling layers, and fully connected layers. Dropout was applied to avoid overfitting, and the model was trained with both training and validation datasets. Below is an overview of the model:

- **Conv2D** layers with ReLU activation functions
- **Max Pooling** layers for down-sampling
- **Dropout** layers to prevent overfitting
- **Dense** layers for the final classification

Here’s a brief overview of the model:
- **Trainable parameters**: 1,649,280
- **Non-trainable parameters**: 0
- **Total parameters**: 1,649,280

## Training and Validation
The model was trained for 7 epochs, with batch size set to 32. Training accuracy reached above 99%, while validation accuracy was slightly lower, indicating a well-generalized model.

### Training Accuracy and Loss Graph
![Training and Validation Graph](path/to/training_graph.png)

### Model Accuracy
![Model Accuracy](path/to/accuracy_graph.png)

## Visualizing the Hand Gestures
The images below represent the classified hand gestures from the dataset:

![Hand Gestures](path/to/hand_gesture_images.png)

## How to Run the Project
1. Clone the repository and install the necessary dependencies from `requirements.txt`.
2. Download the dataset from [Kaggle](https://www.kaggle.com/gti-upm/leapgestrecog) and extract it to the project folder.
3. Train the model using the `train_model.py` script.
4. Test the model using the `test_model.py` script on new gesture data.

## References
- [Leap Gestures Dataset on Kaggle](https://www.kaggle.com/gti-upm/leapgestrecog)

