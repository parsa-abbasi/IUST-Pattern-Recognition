# IUST Pattern Recognition Projects
## 1) Sentiment Analysis using SVM
## 2) Boosting for Imbalanced Data
## 3) Offline Signature Verification using Deep Learning

#### 3.1) Problem definition

An offline signature verifier model should be trained using the Convolutional Neural Networks (CNNs). The problem can be interpreted in many ways, such as classifying signatures based on their signatories or detecting that a signature is genuine or forgery. But, the first interpretation was considered at the implementation.

#### 3.2) Dataset

The [UTSig](http://mlcm.ut.ac.ir/Datasets.html) dataset was used in this project, and it can be downloaded from [here](https://drive.google.com/drive/u/1/folders/0B0CjHfsXJLLObEZFNVdoMlFIODg). UTSig has 115 classes containing: 27 genuine signatures, 3 opposite-hand signed samples, and 42 simple forgeries. Each class belongs to one specific authentic person.

#### 3.3) Solution

![InceptionV3](https://drive.google.com/uc?id=18c3Q5kx58NGvHZEmIw13jc8APi18FMDI)

The [*Inception V3*](https://keras.io/api/applications/inceptionv3/) was used as a feature extractor in this project. It's trained by Google on more than a million images from the ImageNet database to classify images into 1000 object categories.

#### References

- 
  Amir Soleimani and Kazim Fouladi and Babak Nadjar Araabi (2016). UTSig: A Persian Offline Signature Dataset. [https://arxiv.org/abs/1603.03235](https://arxiv.org/abs/1603.03235)

## Course Information
* Pattern Recognition
* Fall 2020
* Dr. Morteza Analoui [[Scopus]](https://www.scopus.com/authid/detail.uri?authorId=16835800400)
* Iran University of Science and Technology (IUST) [[Website]](http://www.iust.ac.ir)
* Department of Computer Engineering [[Website]](http://ce-inter.iust.ac.ir)
