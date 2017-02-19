# Region-Growing

I Implemented region growing algorithm for gray-scale images.
Absolute intensity differences are used for region definition. 
The algorithm takes one seed as input from users via clicking a point in the image and returns with segmentation results. 
It uses 8-connectivity of pixels to do segmentation.
It uses image “input1.jpg" along with its ground truth “out1.jpg" to report TP rate, FP rate, and F-score.
