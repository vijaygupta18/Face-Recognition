# Face-Recognition

## *Introduction*

A simple Face Recognition App Built Using OpenCV-Python.

It works on Local Binary Patterns Histograms (LBPH) Face Recognizer
```
cv2.face.createLBPHFaceRecognizer()

```
Idea is to not look at the image as a whole instead find the local features of an image. LBPH alogrithm try to find the local structure of an image and it does that by comparing each pixel with its neighboring pixels.

Take a 3x3 window and move it one image, at each move (each local part of an image), compare the pixel at the center with its neighbor pixels. The neighbors with intensity value less than or equal to center pixel are denoted by 1 and others by 0. Then you read these 0/1 values under 3x3 window in a clockwise order and you will have a binary pattern like 11100011 and this pattern is local to some area of the image. You do this on whole image and you will have a list of local binary patterns.

## *Required Libraries*

Install All the Libraries
- OpneCV
```
pip install opencv-contrib-python
```
- NumPy
```
pip install numpy
```
## **NOTE:**

 - To collect the datasets edit the storage directory of datasets and then run the file to collect the data

- Run the Face Recognition.py file to check the recognition system




## [Check the Demo Video Here](youtube.com)

```diff
@@ Feel free  to contact us for PRs and Improvements in this project. @@ 


