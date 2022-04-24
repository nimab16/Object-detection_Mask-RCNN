# Object-detection_Mask-RCNN
The goal is to train a model based on Matterport (Mask RCNN) to detect and segment an object. This Transfer learningis based on COCO dataset. We should create our own dataset and annotate the object with Via annotator polygon. 
The object that I choose should not be included in the COCO dataset.I used Acoustic Guitar as a new object that is not in
COCO dataset. I change some hyper parameters like the number of epochs and the learning rate to see the effect on the training results.
Finally, the result of training should be declare as validation accuracy, training loss and some images that shows the segmentation and detection. In addition there is a part of discussion that is regarding to difficulties and the steps for solving them.

# Materials and Libraries
At the first step, the object for training and validation should be annotated by a human. I use https://www.robots.ox.ac.uk/~vgg/software/via/via_demo.html and Polygon selector to segment the region of Gitar. The output of these annotation is a Json file. ( you can find the images and Json file in the dataset part ).


