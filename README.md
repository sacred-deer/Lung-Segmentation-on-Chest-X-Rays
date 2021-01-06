# Lung Segmentation in Chest X-Rays

**Keywords** - Medical Image Analysis, Computer Vision, Deep Learning, Python, Keras 	

### Quick Project Description -
  - Application of computer vision in medical image analysis
  - The [dataset](https://drive.google.com/drive/folders/1-sjbX4TFHwzkej-4IBYjlUyumli2or8V?usp=sharing) contained 704 chest x-rays and their corresponding masks (images with lungs segmented). Given the scarcity of annotated medical images and the general requirement of large dataset for deep networks, I used the **U-net CNN deep network**, which can be trained well from very few images.
  - Achieved a dice coefficient of 0.968 and binary accuracy of 98.4%

### Project Repo Navigation
The IPython notebook named &nbsp; &nbsp; _modelTraining_lungSegmentation.ipynb_  &nbsp; &nbsp; contains the python code to build and train the U-net CNN deep learning model

### [Dataset](https://drive.google.com/drive/folders/1-sjbX4TFHwzkej-4IBYjlUyumli2or8V?usp=sharing) Navigation
Folder "CXR_png_new" contains chest x-rays and Folder "masks" contains corresponding masks for training the model
