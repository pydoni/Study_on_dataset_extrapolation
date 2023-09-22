# UNDER CONSTRUCTION

This project is a study on the use of semi-artificial images for dataset extrapolation with the goal to improve object detection/image classification models that rely on images that are hard to get.

To achieve this goal I have used the CycleGAN Architecture, due to the architecture property do preserve the context of the image while changing part of the image, to convert images of good street into streets with potholes, with the converted images I created a series of datasets with real images and datasets with real images mixed with converted images. Then I trained these datasets with YoloV8 framework for the purpose of pothole detection and did metrics comparison.

On the time of the study it was used CycleGAN, but now there are new models that can achieve image conversion with better results and training/inference time, like CUT and SDedit.
