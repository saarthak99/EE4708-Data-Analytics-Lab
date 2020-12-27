#### EE4708 - Data Analytics Lab - July-Nov 2020
##### Final Project : Team Cheems - Saarthak Marathe (ME17B162), Raj Jain (CH17B066)



#### Model can be downloaded from: https://drive.google.com/file/d/1H70uKE6mH0P-jibAWU1be_EftBEGtJhW/view?usp=sharing
Download the model and save it in the same folder as this notebook.


#### Important Note: ####
-------------------------
1. Please make sure that the private dataset is generated through same reshaping technique as the public test dataset.
   As the public-test set has column-wise reshaping to one-dimensional data, we expect the same to be in private dataset, hence the predictor function makes some transpose transformations to align features properly.

2. Please run the function codes for preprocess, and features_add for the code to work as these are required to pre-process the test data.

3. The model can be downloaded from the given drive link. The predict_private_dataset takes two optional arguments - test dataset path and model path in the case where the model and test sets are located in different folders.

