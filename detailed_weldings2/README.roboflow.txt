
demo_1 - v1 2024-12-13 10:38am
==============================

This dataset was exported via roboflow.com on December 13, 2024 at 8:40 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 1068 images.
A are annotated in YOLOv8 format.

The following pre-processing was applied to each image:
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Randomly crop between 0 and 9 percent of the image
* Random rotation of between -10 and +10 degrees
* Random brigthness adjustment of between -7 and +7 percent
* Random exposure adjustment of between -10 and +10 percent
* Random Gaussian blur of between 0 and 0.5 pixels
* Salt and pepper noise was applied to 0.26 percent of pixels


