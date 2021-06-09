# virtual-paint
Computer vision project implemented with OpenCV

Ever wanted to draw your imagination by just waiving any coloured(blue) object in air. In this post we will learn to build an Air Canvas which can draw anything on it by just capturing the motion of a coloured marker with camera. Here a coloured object at tip of finger is used as the marker.

We will be using the computer vision techniques of OpenCV to build this project. The preffered language is python due to its exhaustive libraries and easy to use syntax but understanding the basics it can be implemented in any OpenCV supported language.

Here Colour Detection and tracking is used in order to achieve the objective. The colour marker in detected and a mask is produced. It includes the further steps of morphological operations on the mask produced which are Erosion and Dilation. Erosion reduces the impurities present in the mask and dilation further restores the eroded main mask.
# Motivation for the idea for this virtual paint

The initial motivation was a need for a dustless class room for the students to study in. I know that there are many ways like touch screens and more but what about the schools which can’t afford it to buy such huge large screens and teach on them like a T.V. So, I thought why not can a finger be tracked, but that too at a initial level without deep learning. Hence it was OpenCV which came to the rescue for these computer vision projects.

# How Air Canvas type of Computer Vision Projects Work ?
Here, We will see the working of this computer vision project in four major points :

1.Understanding the HSV (Hue, Saturation, Value) color space for Color Tracking. And tracking the small colored object at finger tip.
2.Detecting the Position of Colored object atcolour object top and forming a circle over it. That is Contour Detection.
3.Tracking the fingertip and drawing points at each position for air canvas effect. That is Frame Processing.
4.Fixing the Minor Details of the code to function the program smoothly. Algorithmic Optimization.
