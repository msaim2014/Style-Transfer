# Style Transfer User Guide

## Instructions
* Keep pressing shift+enter until reaching Setup Part 2: Directory Setup

* Run the first block of code in that section. That block has created directories where P6_Final_Notebook.ipynb file is located. The file names are base_image, style_image, and generated_image.

* Now you need to insert the images in their respective folders (I have tested this program out with PNG and JPEG only) NOTE: The larger the images the more time and it's going to take because there will be a need for more iterations. I would recommend images around the size of 300*300.
  - base_image folder contains the content image that will have the contours of the generated images.
  - style image folder contains the style image that will have the colors and texture of the generated image.

* The last block of code in Part 2: Directory Setup will ask for the name of the image in the base_image and style_image folder.
  - What is the name of the base image? base_image_example.jpg
  - What is the name of the style image? style_image_example.jpg
  - Are you sure these are the correct names: type (y) for Yes or (n) for No If yes the program will continue but a no will prompt for the names again.

* Now keep pressing shift+enter until you reach the Comparison section. You could run that if you want, but it will give similar results with different parameters

* The mixed style transfer image will be saved in the generated_image folder with the name mixed_image.jpg. Open and view the results.

## Complete
# Style-Transfer
