# CMPE-255 - Bonus Work

SJSU ID : 016040648
Name : Vinay KUmar Reddy Seelam


To train one model (tensorflow or pytorch) and deploy the model by selecting one of the following features: 

1) Using Intel’s OpenVINO Links to an external site.for inference

2) Deploy to Nvidia DeepStream Links to an external site.

3) Deploy to NVIDIA Triton Inference Server Links to an external site.

4) Deploy via Torch Serve Links to an external site.

5) Deploy to TF Serving Links to an external site.

6) Inference via Torchscript Links to an external site.

6) Serving with REST APIs (e.g., Python Flask or Nodejs)

7) Inference via Mobile device (Android or iOS) with acceleration Compare the inference performance improvement (e.g., speed improvement over the original TF/Pytorch inference) of your selected feature.

Add the changes and comparison to the readme (GitHub readme or a separate document), submit the code link (github) to Canavs

Selected Option : Option 1 : OpenVINO

Experiment : Multiclass classification

Dataset Used : Flower dataset in the tensorflow which more than three thousan color images with each belongs to atleast one of the class.

https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz

OpenVINO: OpenVINO is  an open-source toolkit for optimizing and deploying AI inference which boost deep learning performance in computer vision, automatic speech recognition, natural language processing and other common tasks and Uses models trained with popular frameworks like TensorFlow, PyTorch and reduce resource demands and efficiently deploy on a range of Intel platforms from edge to cloud.


Firstly training the model with tensorflow and the optimizing it using OpenVINO and running the interface and comparing performances.

Visualisation Results : 

1.Time taken by OpenVINO vs Tensorflow Inference

![image](https://github.com/vinaykumarseelam/255_Bonus_Work/blob/main/255_BarGraph.png)

Graph representing the various time by the model to predict the class labels in normal tensor flow environment vs that in OpenVINO envirnoment, we can clearly see that OpenVINO takes a way less time than that of the Tensorflow inference for various test sizes.


![image](https://github.com/vinaykumarseelam/255_Bonus_Work/blob/main/255_LineGraph.png)


This Graph Represents the memory usage for various test size

![image](https://github.com/vinaykumarseelam/255_Bonus_Work/blob/main/255_bar.png)




![image](https://github.com/vinaykumarseelam/255_Bonus_Work/blob/main/255_Line_mem.png)

















