# Object Detection and Cropping in Video Files

### Overview

This project processes video files in .mp4 format to automatically detect objects in each frame and save the cropped images of these objects into a specified folder. The solution uses the YOLOv8 model for object detection.

### Features

Input: .mp4 video files (minimum length: 5 to 10 minutes).

Output: Folder with cropped images of detected objects.

### Prerequisites

Google Colab account

Basic knowledge of Python and Google Colab

Setup

### Open Google Colab:

Go to Google Colab

### Install Dependencies:

!pip install ultralytics

### Download YOLOv8 Weights:

Ensure the yolov8s.pt model weights are available in your working directory.

### Credits

This project utilizes the YOLOv8 model provided by Ultralytics. For more information on YOLOv8, please visit the [official YOLO repository](https://github.com/ultralytics/ultralytics).
