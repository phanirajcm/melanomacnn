# Project Name
> Melanoma Detection using Convolutional Neural Networks (CNN)

## General Information
- Problem Statement
	Melanoma is a type of skin cancer responsible for 75% of skin cancer-related deaths. Early detection of melanoma can significantly improve treatment outcomes. This project aims to build a deep learning model that accurately identifies melanoma from skin images, aiding dermatologists in early diagnosis and reducing manual diagnostic efforts.

- Data Set
	The dataset contains images of skin lesions with corresponding labels indicating the presence of melanoma. 
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Training
	Number of Epochs: 20 (initial), 50 (final)
	Loss Function: Categorical Crossentropy
	Optimizer: Adam
	Learning Rate: 0.001
- Initial Training Results:
	Best Accuracy: 0.7597
	Best Validation Accuracy: 0.5213
	Final Validation Loss: 1.9012
- After Augmentation:
	Best Accuracy: 0.2902
	Best Validation Accuracy: 0.3199
	Final Validation Loss: 11.1781
- Final Results (after balancing and further tuning):
	Best Accuracy: 0.9444
	Best Validation Accuracy: 0.8864
	Final Validation Loss: 0.3759


- Results
	The final model achieved the following metrics:

		Training Accuracy: 0.9444
		Validation Accuracy: 0.8864
		Validation Loss: 0.3759
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Requirements
	Python 3.x
	TensorFlow 2.x
	NumPy
	Pandas
	scikit-learn
	Matplotlib
	OpenCV
	Augmentor (for data augmentation)
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by Melanoma Detection using Convolutional Neural Networks (CNN) excercise. Special thanks to Upgrad for this excercise.

- The methodologies and ideas built upon earlier research in the field/s of Machine Learning and Artificial Intelligence.


## Contact
- feel free to contact me!