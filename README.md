# Traffic-Sign-Classifier
A traffic sign classifier for self-driving cars using CNN and FNN.
# Methedology
- Import images from the dataset.
- Preprocessing of images, such as shuffling, greyscaling, histogram equilization, and normalisation.
- Runnibg CNN and FNN for training.
- Running the session to begin the training
- testing model accuracy by testing through a random image.

# Challenges
1. The accuracy on training and testing set was very poor even on applying various types of image preprocessing.
2. The image uploading turned out to be tricky if not uploaded within a dedicated time span of running cell.

# Resolution
1. Introduce third and forth arguments 'mean' and 'stddev' in both CNN and FNN, where mean = 0 and stddev = 0.1
2. Upload the image while the cell is still running, this will ensure that the file is stored in correct folder in Google Drive.

# Datset: 
It can be downloaded into your local pc at https://d17h27t6h515a5.cloudfront.net/topher/2017/February/5898cd6f_traffic-signs-data/traffic-signs-data.zip

# Final Result2
The training set reached an accuracy of 91.7 % with test set reaching a decent 82.1 %

# Future Work:
Add multiple hidden layers so as to increase the efficiency. A proper observation of VGG 16 or Lenet architecture may also enhance the accuracy of the result.
