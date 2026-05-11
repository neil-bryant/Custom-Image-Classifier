Custom-Image-Classifier

Google Collab
https://colab.research.google.com/drive/14lg7TLGnOf-R2d3t32tDmgTg4UX6YbSS?usp=sharing

https://drive.google.com/drive/folders/1fz8Q_8FbA6DLB_MX6TLE2_w4T-x489TN?usp=sharing

Guide Questions (Student Reflection & Explanation)

1. Dataset Preparation
 How did you organize your dataset in Google Drive?

The dataset was organized into separate folders for each class in Google Drive. This structure is important because TensorFlow uses folder names as labels when loading images.

○ Why is folder structure important for TensorFlow image loading?

Convolutional layers detect image features like edges and shapes. The data is split into training and validation sets so the model can learn and then be tested on unseen data.

2. Model Training

○ What is the role of convolutional layers in image classification?
Convolutional layers detect image features like edges and shapes.

○ Why do we split data into training and validation sets?

The data is split into training and validation sets so the model can learn and then be tested on unseen data.

3. Performance Analysis

 What accuracy did your model achieve?
 
 The model achieved around  validation accuracy.

How did the number of images affect the model’s performance

The number of images greatly affects performance, because more images help the model learn better and reduce misclassification.

4. Critical Thinking

○ What challenges did you encounter while using your own dataset?

One challenge was collecting and labeling enough images, especially when some images look similar.

○ How can data augmentation improve your model?

Data augmentation helps by creating variations of images to improve learning.

5. Application

○ Suggest a real-world application for your trained model.

The model can be used for orchid identification, such as recognizing Phalaenopsis, Cattleya, and Dendrobium.

○ How can this system be integrated into a mobile or web application?

It can be integrated into a mobile or web app where users upload an image to identify the plant.

Guide Questions (Student Explanation & Reflection)

Visualization & Overfitting

1. What signs indicated overfitting in your first model?

Overfitting was shown when training accuracy was high but validation accuracy was low.

2. How did data augmentation affect validation accuracy?

   Data augmentation improved validation accuracy by adding more image variations.

Model Improvement

3. What is the purpose of dropout layers?

Dropout layers prevent overfitting by randomly disabling some neurons during training.

4. Why does data augmentation improve generalization?

It creates different versions of images, helping the model learn more patterns and perform better on new data.
Performance Comparison

5. Compare accuracy before and after improvements.

  Accuracy increased after applying data augmentation and dropout.

6. Which technique contributed most to improvement?

Data augmentation contributed the most because it increased dataset diversity.

Deployment & Application

7. Why is saving the model important?

Saving the model allows it to be reused later without retraining.


8. How can this model be deployed in a real-world system?
   The model can be used in a web or mobile app where users upload an image and the system predicts the object or plant,         such as identifying orchids like Phalaenopsis or Cattleya.

