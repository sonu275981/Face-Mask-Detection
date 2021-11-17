
# Face-Mask Detector

Real time face-mask detection using Deep Learning and OpenCV

## About Project

This project uses a Deep Neural Network, more specifically a Convolutional Neural Network, to differentiate between images of people with and without masks. The CNN manages to get an accuracy of 98.2% on the training set and 97.3% on the test set. Then the stored weights of this CNN are used to classify as mask or no mask, in real time, using OpenCV. With the webcam capturing the video, the frames are preprocessed and and fed to the model to accomplish this task. The model works efficiently with no apparent lag time between wearing/removing mask and display of prediction.

#### The model is capable of predicting multiple faces with or without masks at the same time

## Working

### Mask

![Alt text](https://github.com/sonu275981/Face-Mask-Detector/blob/ee2675a213650a3c593183bbc8464d374be852ce/testing_live/Mask.png?raw=true "Face-Recognition-Attendance-System")

### No-Mask

![Alt text](https://github.com/sonu275981/Face-Mask-Detector/blob/ee2675a213650a3c593183bbc8464d374be852ce/testing_live/No-Mask.png?raw=true "Face-Recognition-Attendance-System")

## Dataset

The data used can be downloaded through this link or can be downloaded from the Kaggle as well (folders 'test' and 'train'). There are 10,000 training images and 992 test images as well as 800 validation images divided into two catgories, with and without mask.

## How to Use

To use this project on your system, follow these steps:

1.Clone this repository onto your system by typing the following command on your Command Prompt:

```bash
  git clone https://github.com/sonu275981/FaceMaskDetector.git

```

followed by:

```bash
  cd FaceMaskDetector

```

2. Download all libaries using:

```bash
  pip install -r requirements.txt

```

#### The Project is now ready to use !!



