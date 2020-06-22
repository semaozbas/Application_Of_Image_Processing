# Application_Of_Image_Processing
Face Recognition with Transfer Learning
#### Group Member
- Fahrulnisa Sema Özbaş
- Ibrahim Berber
#### Requirements
- MATLAB R2019a
- USB/Internal webcam
### DATABASE
The database used is available at link https://fei.edu.br/~cet/facedatabase.html
</br></br>In the dataset, there are 200 different young and middle-aged individuals and each image taken with 14 various perspective such as different orientation, brightness etc.
### DATABASE PROCESSING 
For extract unpractical images and testing images foldering.py can be used. After that _FaceDatabase file is created automatically.
1. Put all images to database_processing\images
2. Run foldering.py file
### GUI REGISTRATION 
You can take your photos with GUI_REGISTRATION part. You must fill drive name part in GUI and system automatically creates a file with the name of the driver.
### TRAIN THE MODEL
In this part you  can train data and save. In folder we upload already trained model. You can train your own model  with including your images. This is clearly explained in section GUI_REGISTRATION.
1. Train data
2. Save trained model
### AUTORIZED DRIVER
An authorized_users part for access drivers who  allow from system.You can use face_registration\driver.py for add/remove users.
### TEST THE MODEL 
You can see the estimate of the image you are inquiring about the model and see if the application is allowed to user to enter the car, depending on whether the photo is on the list.
1. Select image
2. Run input_testing.m file
### DEMO VIDEO
https://youtu.be/xd6nh1Ohc3Y


