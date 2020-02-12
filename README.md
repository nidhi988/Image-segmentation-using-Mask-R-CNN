# Image-segmentation-using-Mask-R-CNN

Some Initial steps before working on python code:

Mask R-CNN Installation
git clone https://github.com/matterport/Mask_RCNN.git    on command line

cd Mask_RCNN
python setup.py install

pip show mask-rcnn     # to check installed mask cnn library

Download Model Weights to current working directory
mask_rcnn_coco.h5

Download sample photo of your choice

Load Model and Make Prediction
First, the model must be defined via an instance MaskRCNN class.
This class requires a configuration object as a parameter. The configuration object defines how the model might be used during training.
