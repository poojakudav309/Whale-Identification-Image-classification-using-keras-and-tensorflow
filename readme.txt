Humpback Whale identification challenge Kaggle:

Project Requirements:

For UNIX:
Install Python 3.6
Install ipython
Install virtualenv 
Install tensorflow 
create and use virtualenv <give-your-env-name>
Install Keras
Install Jupyter (in case of accessing notebook via chrome browser, for unix-non-GUI servers)
Numpy
scipy
sklearn
matplotlib
shutil
openCV
os
PIL
copy
skimage
kaggle


For WIndows:

Install Anaconda
Install packages from anaconda: 
Keras-tf
tensorflow
Numpy
scipy
sklearn
matplotlib
shutil
openCV
os
PIL
copy
skimage


1. Preprocessing instructions(Basically we are supposed to create test and validation folders out of train folder)

	Make two folders test and validation from the preprocess notebook run the code(Do not have to do this step as we have already done that and included the training and validation datasets) but still walking through the steps:
	1. Make folder for each class (code in notebook file).
	2. Organize images into respective folders (code given in the preprocessing notebook file)
	3. Move the most significant 30 classes to a separate folder for both test and valid 
	4. Data Augmentation for training file. (Code given in notebook file)
	NOTE: Please update the path for train and validation files in the code manually.

2. Running the model:
	1. Run Basic CNN Model (code given in notebook file)
	2. Run VGG_16 model (code in notebook file)
	NOTE: The model will take some time to run, and it depends on the input data size. 
	
3. Testing an image
	1. pick an image from test folder and run the testing code given in notebook file.
	Note: The Kaggle dataset for test does not have labeled images, So we picked 10 random images and names the images with their class names and tested it.
	
	

