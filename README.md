# Age-and-Gender-Recognition

We will use Haar cascades to detect faces and then use Convolutional Neural Network (CNN) to predict the age and gender of the people in the image/ video frame.

The program can take input from a saved image or video and also from web cam and giving live results.

We will be using the already available trained data (caffe models) and import them using the dnn package prodived by OpenCV.

### Requirements
1. [OpenCV](https://opencv.org/about/)
2. [Haar-Cascades](https://docs.opencv.org/trunk/d7/d8b/tutorial_py_face_detection.html)
3. [Caffe Models](https://caffe.berkeleyvision.org)  
    A caffe model has 2 associated files,  
         **prototxt** — The definition of CNN goes in here. This file defines the layers in the neural network, each layer’s inputs, outputs and functionality.  
         **caffemodel** — This contains the information of the trained neural network (trained model).

### Downloads
**OpenCV** - `pip install OpenCV-python`  
Download **haar cascade** for face detection from [here](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)  
Download the age and gender classification files (**caffe models**) and deploy protext files from [here](https://talhassner.github.io/home/publication/2015_CVPR)

### Example with saved Video as input
![](https://cdn-images-1.medium.com/max/800/1*t4SZZRjmQudyuerPyzfp8A.gif)

### References
1. [Age and Gender Classification Using Convolutional Neural Networks](https://talhassner.github.io/home/publication/2015_CVPR)
2. [How to build a face detection model in python]https://medium.com/analytics-vidhya/how-to-build-a-face-detection-model-in-python-8dc9cecadfe9
