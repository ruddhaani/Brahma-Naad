# Brahma-Naad

This project is an ML model that uses OpenCV, TensorFlow, GTTS, Playsound, and Mediapipe Holistic to convert Sign Language (ASL) to Audio.

## Overview

The ASL to Audio Converter uses a combination of computer vision and deep learning techniques to recognize hand gestures in real-time and translate them into audio. The system utilizes a trained TensorFlow model to detect hand gestures from video input, which is captured using OpenCV. The detected hand gestures are then mapped to corresponding audio output using Google Text-to-Speech (GTTS) and Playsound libraries. Mediapipe Holistic is used to detect and track the pose and movements of the entire body, providing a more comprehensive understanding of the context of the signing.

## Requirements

* Python 3.x
* Tensorflow 2.x
* Tensorflow-GPU 2.x
* OpenCV
* Mediapipe
* Scikit Learn
* GTTS
* Playsound

## Installation

* Clone the Repository
* Install the required libraries - `pip install tensorflow opencv-python mediapipe sklearn matplotlib gtts playsound==1.2.2`
* Open your Jupyter Notebook and Upload the cloned floder

## How to use the Project

* A pre-trained model is already provided , so u can directly run the Test.ipynb file .
* However , if you wish to train the model kindly run the Train.ipynb file , a Folder with name 'Data_New' will be created , move the contents of 'Data-New' to 'Data'.
* Now, to save the model use the 'SavingModel.ipynb' file.

##Demo of the Project

https://user-images.githubusercontent.com/99528334/234953291-c33cc249-d00a-4a6a-8b5b-9a7d64164171.mp4


