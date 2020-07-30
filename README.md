# How to wrap images by mouse clicking!
In this project I will  show how to use `warp perspective` function
 In openCV and transform images from to `angle 
 perspective` to a `bird view` like this:
 
 
 ![warp](warp.png)

## Algorith
- Importing libraries : cv2 and numpy
- Write standard openCV funtions to read and show image
``` python
import cv2
import numpy as np
img = cv2.imread('1.png')
cv2.imshow('Original Image',img)
cv2.waitkey(1)
```


