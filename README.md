**EmotionEye: Real-Time Facial Emotion Recognition**

EmotionEye is a facial emotion recognition system designed to classify emotions in real-time using deep
learning techniques. This project leverages convolutional neural networks (CNNs) with TensorFlow and
Keras, and OpenCV for facial detection, to accurately identify emotions such as happiness, sadness,
anger, surprise, and neutrality.

Features

● Real-time emotion recognition

● Supports seven emotion categories: Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise

● Implements a CNN model trained on the FER2013 dataset

● Utilizes OpenCV for facial detection and image preprocessing

Prerequisites

● Python 3.6+

● Required Python packages (see Installation)

Steps to Run EmotionEye

1. Clone the Repository

git clone https://github.com/yourusername/EmotionEye.git

cd EmotionEye

2. Install Required Packages

Install the required packages listed in requirements.txt:

pip install -r requirements.txt

Make sure opencv-python-headless is also installed for facial detection:

pip install opencv-python-headless

3. Add Model Files

Place the following pre-trained model files in the project’s root directory:

● facialemotionmodel.h5 — contains the model weights

● facialemotionmodel.json — contains the model architecture

4. Run the EmotionEye Application

Start the application to capture webcam input, detect faces, and classify emotions in real-time:

python facedetection.py

The application will open your webcam, detect faces, and display the predicted emotion for each detected
face in real-time.

Additional Notes

● Ensure your system webcam is accessible for OpenCV.

● If running the model on a different device, adjust paths in facedetection.py if needed


