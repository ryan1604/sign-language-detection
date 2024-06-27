# Sign Language Detection using Action Recognition

This project aims to build a deep learning model to detect sign language gestures using Long Short-Term Memory (LSTM) networks.
The model processes a sequence of hand movements and predicts the corresponding sign language gestures.

The dataset used consists of sequences of hand movements captured using a camera. 3 sign language gestures were used, with
30 videos for each gesture for a total of 90 videos. The gesture that this model will predict is 'hello', 'thanks', and
'i love you'

## Requirements

- Python
- TensorFlow
- OpenCV
- NumPy
- Scikit-learn
- Mediapipe

## Evaluation

The model can successfully predict the correct sign language gesture most of the time. Mediapipe holistic is used to
reduce the amount of training data required, which makes it faster to train and also provides faster detections.

The performance can be improved by taking the videos at better positions and angles.
