# tensorflow_study
Deep Learning - Building Neural Network for Image and Text recognition using Tensorflow
* **NOTE: Kindly access via https://nbviewer.jupyter.org/github/yiwei-ang/tensorflow_study/tree/master/ if you have any issue rendering notebook in GitHub.**
* Neural Network on Sign MNIST dataset.
  - Dataset Source: https://www.kaggle.com/datamunge/sign-language-mnist
  - Data in in csv format containing pixels information.
  - Data Augmentation, CNN building, Drop Out Layer.

* Neural Network on Horses vs Huamn dataset.
  - Dataset Source: http://www.laurencemoroney.com/horses-or-humans-dataset/
  - Data in in csv format containing pixels information.
  - Note that TF will automatically label the diagrams based on subdirectory, ie all the training horse images will be under training/horse
  - Data Augmentation, CNN building, Drop Out Layer.
  - Also, introduce pre-load pretained model from https://github.com/fchollet/deep-learning-models/releases/download/v0.5/inception_v3_weights_tf_dim_ordering_tf_kernels_notop.h5
