# Bioacoustic-Estimation-Of-Avian-Vocalizations-For-Capuchin-Bird-Density-In-Forests
Building a Convolutional Neural Network (CNN) model with TensorFlow to tackle the
challenge of quantifying the density of Capuchin bird calls in
audio clips. The data used is recordings of bird calls, so we need
to identify if there are Capuchin bird vocalizations or not. The
main parts of this study are preparing the data, designing the
model architecture, and comprehensive training. To address
this problem we start by collecting and labeling the dataset,
carefully splitting audio clips and marking them as having or
not having Capuchin bird calls. Feature extraction is really
important, involving turning the raw audio data into useful
features, like Mel-frequency cepstral coefficients (MFCCs) and
spectrograms which are essential for training the CNN and the
TensorFlow CNN model architecture is designed very carefully
to take these audio features as input and give binary
classifications, making predictions on whether a given clip has
Capuchin bird calls or not. An iterative process of tuning
hyperparameters optimizes the model's performance, so it
learns to pick up on the details in the audio data effectively. In
the evaluation phase, the model's accuracy and efficacy are
measured using metrics like precision recall, F1-score, and
validation datasets. If this work is successful, it will provide
researchers and conservationists with a powerful tool to
measure Capuchin bird call density in audio recordings helping
with wildlife monitoring and preservation efforts.
