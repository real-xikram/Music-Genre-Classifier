# Music-Genre-Classifier
Classifies music files in .wav format into 10 genres using KNN

#Dataset
The GTZAN music genres dataset can be found on the link below:
https://www.kaggle.com/carlthome/gtzan-genre-collection

Project Highlights:
- Uses a KNN classifier for 10 musical genres from audio files using their low-level features of the frequency and time domain
- The MFCC features from GTZAN music genre classification dataset are genreated by taking Direct Cosine Transformation of the   frequencies
- The distance measure is a combination of the mean MFCC matrix and its Covariance matrix over 20 ms - 40 ms subframes
- The output class based upon a majority vote of the five nearest neighbors and F1 score of 0.68 on the test dataset is achiveved
- The files to be tested can be done individually by inserting their names into the classification.py or it can be run as a script

Important Note-
              The dataset contains files in .mp3 format and need to be convereted to .wav format
              The coversion.py script has to be run using the terminal to convert the database to .wav format
   
