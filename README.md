# Self-Driving-Car--Lane-Line-Finding
This project shows us how to find lane line in a video

# Pipeline description 

a. Converting the image into grey scale 
b. Used open cv function Gaussian blur for smoothing out the image 
c. Detected the images using Canny edge detection  
d. Created region of interest on the Canny edge detected image 
e. Performed Hough transform to detect line segment 
f. Draw lines on a binary mask on a blank image and combine it with input image to get final overlay output.  
g. Extrapolate the line segments to map the full extent of the lane.  


 
