import webbrowser to open browser

import math to find angle edges (finger)

import os to use operating system dependent funtionality

#1. start capture the video 

To fine angle between edge we need to detect edge which is edge detection .

we use "contour" in opencv to detect the edge . 

To use contour (Used in objrct detection) need to have Binary Image.

So need to have threshold image .

Threshold image need a blur image (remove noise). 

Blur image need gray image . 



PROCESS TO OPEN BROWSER USING FINGER EXPRESSION


             Gray Image
                 |
            Blur Image
                 |
            Threshold Image
       	         |
              Contour 
                |
            Convex Hull
                |
            Find Angle
               |
            Open Browser  
    
