_**What is Glaucoma?**_
Glaucoma is a chronic eye condition that damages the optic nerve, often due to increased intraocular pressure. It is a leading cause of irreversible blindness worldwide. Glaucoma is typically asymptomatic in its early stages but can result in gradual peripheral vision loss and, if untreated, complete blindness. Regular eye exams are essential for early detection, as timely treatment—such as medications, laser therapy, or surgery—can slow its progression.

![image](https://github.com/user-attachments/assets/9383b1fe-57bb-4810-b4ec-bd8a587d1f75)


_**DATASET DESCRIPTION**_

**ACRIMA**
	ACRIMA database is composed by 705 fundus images All images from ACRIMA database were annotated by 	glaucoma experts with several years of experience. They were cropped around the optic disc and renamed.
 
**DRISHTI-GS**
  This Dataset contains 50 train images and 51 test Images. In Each Directory there are two folders one is images and the second one is GT. The later folder contains Optic Disk and Cup masks associated with the images in the Images folder.
  
**RIMONE**
  The RIM-ONE database contains 169 optic nerve head images. Each image has 5 manual segmentations from ophthalmic experts. A gold standard for each image was created from its corresponding segmentations.

**INDIVIDUAL DATASETS**

  https://www.kaggle.com/datasets/toaharahmanratul/acrima-dataset
  https://www.kaggle.com/datasets/lokeshsaipureddi/drishtigs-retina-dataset-for-onh-segmentation
  https://www.kaggle.com/datasets/lucascunhadecarvalho/rimoner2
  
  ![image](https://github.com/user-attachments/assets/fc1f0733-e26c-4216-84fc-8b19beaee128)

  We considered 3 different datasets and combined them to become a large dataset. The primary step of any model building will be pre-processing of the data. The pre-processing of data means converting the raw data into required form so that the analyzation becomes easy. The preprocessing and data augmentation is done by image data generator. The augmented images are then sent for feature selection. In the feature extraction and classification we are using  Convolutional neural network. As we know neural networks are composed of many layers like convolution,pooling, fully-connected layers etc., And also have activation functions. CNN takes image as input for training. This may improve the prediction accuracy of the model. Based on the  amount of pressure, the stage of the glaucoma can be determined.

  **Samples in each derived class**
![image](https://github.com/user-attachments/assets/5f27f6fe-53d6-4b58-93c0-e03dd6933ea0)

_**METHODOLOGY**_
![image](https://github.com/user-attachments/assets/0490094f-1a6d-450a-9885-8f74230645f1)

_**Directory Structure**_
![image](https://github.com/user-attachments/assets/d03d8e24-8e32-467c-a163-432d317013f5)

![image](https://github.com/user-attachments/assets/04a30328-911d-49e9-b371-1fbdd5b0a4f1)



