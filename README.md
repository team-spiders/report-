#            Face Detection Using Viola-Jones Object Detection Framework


```
      AKASH GHIMIRE     BIJAY PARIYAR    KESHAV ADHIKARI      THAPA PRADIP

        12194814           12194945          12194874           12194940
        
```
## Project Objective:

In this project we implement the face-based object detection algorithm proposed by Viola and Jones (2001). This Project uses Haar Cascade technique along with adaBoost training system for face detection by taking hundreds of positive face images with respect to thousands of negative non-face images.  

Face detection employs classifiers, which are algorithms that determine whether something in a picture is a face(1) or not a face (0). To improve accuracy, classifiers have been trained to recognize faces in tens of thousands to millions of photo. Haar Cascade is one of the most common classifiers in OpenCV.     


## Haar Cascade:

The Haar Cascade classifier divides the pixels in the image into squares depending on their functions using the Haar Wavelet approach. The "features" that are detected are computed using "integral image" principles. The Ada-boost learning algorithm is used by Haar Cascades, which picks a small number of crucial features from a huge set to get an effective output. Cascading techniques are then used by classifiers to recognize faces in images. Some Haar-Features are listed below.

![image](https://user-images.githubusercontent.com/115747921/200088402-7dec1445-99e2-4dda-8299-e9f01257e665.png)
```
                       Fig 1: Haar feature extraction kernels
```

## Datasets:
There are two types of data set we have used for this project:

I) _**Custom dataset**_:
      
For custom dataset we have used Q51 13 megapixels camera, in order to maintain picture quality and capture several images per minute we have used photo burst application.
 
 For custom dataset we have divided each team members image dataset into 6 sub folders of 6 challenging aspects of object detection according to the variations and orientations and illumination conditions:


1) *Viewpoint variation*

2) *Deformation*

3) *Occlusion*

4) *Illumination conditions*

5) *Cluttered or textured background* 

6) *Intra class variation* 



we have taken various wide range as well as short range images along with vertical orientations.



![image](https://user-images.githubusercontent.com/115747921/200090177-f710acc8-34a0-4fc4-9059-ee90533feec3.png)
```
    fig 2: Custom data-set with 6 different challenging aspects of object detection
```


## **Positive and Negative Images**

It’s important to remember that this algorithm requires a lot of positive images of faces and negative images of non-faces to train this classifier. A positive image is one containing an object that must be detected and a negative image is the one that is not need to find or detect object.

*In our case, for positive images we have taken self made face images into account, and for negative images we have taken images of non-face object that are available inside of our houses*.

```
 fig3: custom made positive images
 ```
 
 For example, fig 3 are the examples of our custom-made positive images that we will be putting as an object that needs to be detected using classifier.

