# motion-detector
This python program will allow you to detect motion and also store the time interval of the motion.

Requirement: 

Python3
OpenCV(libraries)
Pandas(libraries)

Analysis of all windows 
After running the code there 4 new window will appear on screen. Let’s analyze it one by one: 




1. Gray Frame : In Gray frame the image is a bit blur and in grayscale we did so because, In gray pictures there is only one intensity value whereas in RGB(Red, Green and Blue) image thre are three intensity values. So it would be easy to calculate the intensity difference in grayscale. 
 



2. Difference Frame : Difference frame shows the difference of intensities of first frame to the current frame. 



3. Threshold Frame : If the intensity difference for a particular pixel is more than 30(in my case) then that pixel will be white and if the difference is less than 30 that pixel will be black 



4. Color Frame : In this frame, you can see the color images in color frame along with green contour around the moving objects 

