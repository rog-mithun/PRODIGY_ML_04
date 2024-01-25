# PRODIGY_ML_04


Hand Gesture Recognition using Convolutional Neural Network
This repository hosts the code for training a Convolutional Neural Network (CNN) to recognize hand gestures, utilizing the LeapGestRecog dataset. The dataset comprises infrared images organized by subjects and gestures. The CNN model, defined with convolutional and max-pooling layers, achieves a test accuracy of 95%. Model weights and architecture are saved for future use. A prediction script is provided to make predictions on new images, displaying both the predicted gestures and their corresponding images.

Dataset
The LeapGestRecog dataset is structured by subjects and gestures, with each subject's infrared images categorized by hand gestures.

Dataset :-  https://www.kaggle.com/gti-upm/leapgestrecog

Getting Started
Clone the repository:
git clone https://github.com/manisha-31/PRODIGY_ML_04.git

Install dependencies:
pip install -r requirements.txt
Download the LeapGestRecog dataset and place it in the root directory:

Train the model:
python train_model.py
 
Make predictions on new images:
python predict_gestures.py


Model Architecture
The CNN model consists of convolutional and max-pooling layers, followed by fully connected layers. It is trained using the RMSprop optimizer and categorical crossentropy loss.

Evaluation
The model is evaluated on a test set, achieving a test accuracy of 95%. Model weights and architecture are saved.

Making Predictions
The trained model is loaded, and predictions are made on new images. Predicted gestures and corresponding images are displayed.
