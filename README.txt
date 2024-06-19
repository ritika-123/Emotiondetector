MNNIT Allahabad
B.Tech. (IT) 2019 Batch
Group 11

UTKARSH MANI TRIPATHI (20158027)
VRINDA AGARWAL (20158103)
ANKIT GARG (20153069)
VIVEK KUMAR JHA (20158073)
KSUHAGRA SHUKLA (20158075)


This project, titled "Human Emotion Detection (H.E.D.) through Recognition of Facial Expressions", has been developed in python 3.6 (64-bit).

Upon installation of Python 3.x on your 64-bit machine, install pip (in Command Prompt).

Necessary dependencies in Python 3.6 are :
Numpy
Keras
Pandas
Tensorflow
OpenCV2
Skimage
Matplotlib
Statistics
Sklearn

For installing a dependency, Open Command Prompt (as Administrator) and type :
	pip install <dependency_name>
	OR
	python -m pip install <dependency_name> --user

Running the Training modules : [takes nearly 50 hrs to train]
Open Command Prompt (as Administrator) in the project folder location.
Type in CMD : Train.py

Upon model training, the trained CNN model is stored in the location: 
.\training_output\fer2013_mini_XCEPTION.94-0.66.hdf5

Running the Test modules :
Open Command Prompt (as Administrator) in the project folder location.

1. Test With Still Image
Type in CMD : "Test with Image.py"

2. Test with Video File [uses file "TestVideo.mp4"]
Type in CMD : "Test with Video file.py"

3. Test with Live Camera [requires WebCam]
Type in CMD : VideoTest.py

Enjoy!