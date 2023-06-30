# Object Detection with PixelLib

![License](https://img.shields.io/badge/License-MIT-blue.svg)

This project demonstrates object detection in images and videos using the PixelLib library. PixelLib is a powerful library for object detection, instance segmentation, and image and video editing.

## Features

- Object detection in images
- Object detection in videos
- Instance segmentation
- Pre-trained models available
- Custom training option

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Install the necessary dependencies: pip install pixellib opencv-python
   
2. Download the pre-trained model weights from the PixelLib model zoo.

- For image object detection: [Download Link](https://github.com/ayoolaolafenwa/PixelLib/releases/download/1.2/mask_rcnn_coco.h5)
- For video object detection: [Download Link](https://github.com/ayoolaolafenwa/PixelLib/releases/download/1.2/xception_coco_voctrainval.h5)

## Usage

1. Object Detection in Images:

- Run the following command to perform object detection on an image:

  ```
  python detect_face_image.py
  ```

- Replace the image path present in the code.

2. Object Detection in Videos:

- Run the following command to perform object detection on a video:

  ```
  python detect_face_video.py 
  ```

- Replace the video path present in the code.
  

## Contributing

Contributions are welcome! If you have any ideas, improvements, or bug fixes, please submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
