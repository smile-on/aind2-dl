# AIND-DL

This is a copy of Udacity [introduction into deep learning](https://github.com/udacity/aind2-dl) project with minor bug fixes and all notes collected in one place. Project uses Keras high level wrapper for Neural Networks with Tensorflow as back-end.


##Installation instructions

1. It is assumed you have **Anaconda** python environment [installed](https://conda.io/docs/user-guide/install/index.html).

2. Clone the repository and navigate to the downloaded folder.

  ```	
  	git clone https://github.com/udacity/aind2-dl.git
  	cd aind2-dl
  ```

3. Obtain the necessary Python packages, and switch Keras backend to Tensorflow.  

  For __Linux__:
  ```
  	conda env create -f requirements/aind-dl-linux.yml
  	source activate aind-dl
  	KERAS_BACKEND=tensorflow python -c "from keras import backend"
  ```

  For __Windows__:
  ```
  	conda env create -f requirements/aind-dl-windows.yml
  	activate aind-dl
  	set KERAS_BACKEND=tensorflow
  	python -c "from keras import backend"
  ```
  For **Mac/OSX**:
  ```
    	conda env create -f requirements/aind-dl-mac.yml
    	source activate aind-dl
    	KERAS_BACKEND=tensorflow python -c "from keras import backend"
  ```

4. Enjoy!

  ```
  	jupyter notebook
  ```

  part 1 - [Student Admissions](Student_Admissions.md)

  part 2 - [IMDB Movie Data](IMDB_In_Keras.md)

  ​

