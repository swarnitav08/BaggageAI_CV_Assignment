# BaggageAI_CV_Hiring_Assignment

Various image processing techniques like masking with set transparency percentage to trace and isolate threat object, resizing and rotating using imutils resize() and rotate_bound() methods and pasting one image on another using PIL paste() method have been used to complete the given task. The libraries used are OpenCV and PIL (Python Imaging Library) along with imutils, glob and numpy. The order followed for taking threat images is as per given in the folders provided.

Some points to note:

1) Transparency is maintained at 65% for all threat images so that they appear translucent after pasting. Concept of masking has been used to isolate threat object from its background.

2) Scaling down (resizing) has been done based on coresponding background image height has been done for all threat images.

3) Rotate with 45 degree has been done for all threat images.

4) Pasting of threat image on corresponding background image has been done using a mask and the position for placement of threat object is chosen such that it remains inside boundary of background image in all cases.

5) Comments are added wherever necessary for explanation.

6) The folders added with images contain - 

 a) paste_mask images (transparent masks for pasting) 

 b) resized images (resized and rotated threat images)

 c) resized_mask images (resized and rotated masks)

 d) final images (final output with threat object pasted on background images)
