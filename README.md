**Diabetic Retinopathy Classification using CNN**

**Project Overview**

This project develops a Convolutional Neural Network (CNN) designed to classify stages of diabetic retinopathy from retinal fundus images, utilizing the APTOS 2019 dataset. The primary goal is to assist ophthalmologists in early detection and intervention to prevent the progression towards blindness.

Features

	•	Automated Image Processing: Utilizes CLAHE for image enhancement and standard preprocessing to prepare the APTOS 2019 images for optimal analysis.
	•	Custom CNN Model: Features a tailored neural network architecture capable of identifying and classifying various stages of diabetic retinopathy with high accuracy.
	•	Performance Optimization: Implements dropout, data augmentation, and meticulous hyperparameter tuning to ensure robust model performance.

**Data**

The model is trained and validated on the APTOS 2019 dataset, which includes a comprehensive set of retinal images annotated with stages of diabetic retinopathy. The data preprocessing includes resizing, normalization, and augmentation to enhance the model’s ability to generalize from the training data.

Model Comparison

	•	ResNet50: Achieved the highest accuracy at 81%, proving effective in capturing complex visual features from retinal images.
	•	Custom CNN Model: Followed closely with an accuracy of 75%, tailored specifically to optimize performance for diabetic retinopathy classification.
	•	EfficientNetB0: Showed lesser performance at 50% accuracy, highlighting limitations in feature extraction depth for this application.

**Model Training**

The CNN models undergo extensive training and validation processes, ensuring high accuracy and sensitivity in identifying stages of diabetic retinopathy. This includes several epochs and batches to optimize the learning process.

**Validation and Testing**

Rigorous testing and validation are conducted to verify the model’s effectiveness. Performance metrics such as accuracy, sensitivity, and specificity are calculated to assess the model’s diagnostic capabilities.

**Contributions**

Contributions from the community are welcome. Researchers and developers interested in improving or adapting the model are encouraged to share their suggestions and enhancements.

**Licensing**

This project is made available under a standard open-source license, allowing for both academic and commercial use, provided that proper credit is given to the original creators.

**Contact Information**

For further information, support, or to contribute to the project, please contact yash.kulkarni149@gmail.com
