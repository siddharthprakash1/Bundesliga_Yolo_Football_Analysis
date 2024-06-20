output screenshot1:![image](https://github.com/siddharthprakash1/test/assets/92435819/f7192ad3-c73b-4196-935d-b0a884f6df33)
output screenshot2:![image](https://github.com/siddharthprakash1/test/assets/92435819/a1a54e41-04c6-47a4-a40a-66244cfde85d)
output screenshot3:![image](https://github.com/siddharthprakash1/test/assets/92435819/df6f58fb-bb16-400f-aff9-85a79cf9ce89)
# Soccer Video Analysis

This repository contains a Python project that performs various analysis tasks on soccer video footage. It utilizes computer vision and deep learning techniques to detect and track players, balls, and referees, estimate camera movement, calculate player speeds and distances covered, assign team colors, and determine ball possession.I have used yolov8 and yolov5x for this.

## Features

- **Object Detection and Tracking**: Detects and tracks players, balls, and referees throughout the video using a pre-trained YOLOv5x deep learning model.
- **Camera Movement Estimation**: Estimates the camera movement in each frame and adjusts the object positions accordingly.
- **View Transformation**: Transforms the object positions from the camera's perspective to a top-down (bird's-eye) view.
- **Speed and Distance Calculation**: Calculates the speed and distance covered by each player over a specified time window.
- **Team Assignment**: Assigns team colors to each player based on their jersey colors.
- **Ball Possession Assignment**: Determines which player has possession of the ball in each frame.
- **Output Video Generation**: Generates an output video with annotated object tracks, camera movement indicators, and speed/distance overlays.

##  Tech Stack

-YOLOv8 for object detection (main code)
-YOLOv5 for object detection (dataset)
-OpenCV for computer vision functionality
-PyTorch for deep learning models
-Roboflow for dataset management and preparation

##NOTE:
This has many files missing as I was not able to upload my larger files specifically the ".pt" files.So you will have to run the training.ipynb in the training folder and make your own .pt file and also you will have to download dataset from roboflow with your own api key and in that you can use any yolo architecture I chose yolov5x since it was able to detect the football easily and this model was accurate and light weight enough to run on my computer.

