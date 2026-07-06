# Age and Gender Detection using OpenCV

## Project Overview

This project detects faces in an image or webcam feed and predicts the person's age group and gender using pre-trained Deep Learning models with OpenCV.

## Features

- Face Detection
- Gender Prediction
- Age Prediction
- Real-time webcam support
- Uses pre-trained Caffe and TensorFlow models

## Technologies Used

- Python
- OpenCV
- Deep Learning
- Caffe Models
- TensorFlow Face Detection Model

## Project Files

- main.py
- age_deploy.prototxt
- age_net.caffemodel
- gender_deploy.prototxt
- gender_net.caffemodel
- opencv_face_detector.pbtxt
- opencv_face_detector_uint8.pb

## How to Run

1. Install Python.
2. Install OpenCV:

```bash
pip install opencv-python
```

3. Run the program:

```bash
python main.py
```

## Output

The program detects faces and displays:

- Gender
- Age Group

directly on the video or image.

## Author

Shrishail