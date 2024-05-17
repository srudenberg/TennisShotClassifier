# TennisShotClassifier

Data: 
game1 and game8 folders contain individual clip classifications. 
images folder contains the raw image data. 

Processing: 
game1.csv and game8.csv combine the clip information into one data frame. 
game18_2.csv combines the data frame of game1 and game2. 
game182_fixed.csv manually fixed an issue with missing data. 
images2 folder contains the renamed, resized, recolored images. 

Code: 
DataPrep.ipynb contains processing 
Models.ipynb contains CNN model 
3Dcnn.ipynb contains attempt at 3DCNN model 
