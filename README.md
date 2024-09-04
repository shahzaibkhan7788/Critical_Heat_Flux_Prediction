# Critical_Heat_Flux_Prediction

README for Critical Heat Flux Prediction Project
Project Overview
This project focuses on predicting Critical Heat Flux (CHF), a crucial parameter in thermal engineering that represents the maximum heat flux at which a boiling surface can be heated before the onset of a dangerous thermal instability, such as burnout or boiling crisis. Accurate prediction of CHF is vital for the safety and efficiency of thermal systems, including nuclear reactors and other high-heat flux applications.

Models and Methodology
In this project, I have employed several machine learning models to predict CHF using a dataset of 10,000 samples. To improve model performance and generalization, I applied data augmentation techniques, effectively increasing the dataset size to 20,000 samples.

Here’s a summary of the models used:

Simple Decision Tree Regression

Original Data: Applied the model on the original dataset.
Augmented Data: Applied the model on the augmented dataset.
Autoencoder

Original Data: Trained a simple autoencoder on the original dataset.
Augmented Data: Trained a simple autoencoder on the augmented dataset.
Autoencoder with Decision Tree Regression

Original Data: Combined an autoencoder with decision tree regression on the original dataset.
Augmented Data: Combined an autoencoder with decision tree regression on the augmented dataset.
Autoencoder with Random Forest Regression

Original Data: Combined an autoencoder with random forest regression on the original dataset.
Augmented Data: Combined an autoencoder with random forest regression on the augmented dataset.
Best Performance: This approach yielded the best results, achieving an R-squared value of approximately 96%, indicating strong model performance.
