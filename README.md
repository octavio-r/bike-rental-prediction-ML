# bike-rental-prediction-ML
Machine learning is employed to make predictions on a bicycle rental dataset. Initially, linear regression is employed using both NumPy and PyTorch, for educational purposes. Eventually other models shall be implemented as well.

A dataset containing information on bicycle rentals from 2011 to 2012 from the Capital bikesharing system is employed for training. The dataset is split into a training set and a test set in order to test the accuracy of the predictions made after learning.

In a first instance, only linear regression is used for learning. The purpose of this choice is both educational and to showcase the shortcomings of such models. 8 features from the dataset are used for training. The daily rental count is chosen as the target variable. 

After splitting the dataset by keeping 80% of the data for training use and 20% for testing, the linear model showcases no overfitting. However, it does exhibit significant underfitting. For a dataset which mean rental count is roughly 4500, the RMSE of the predictions is 1360, an error of about 30%. This confirms that a linear model is far too simplistic of a choice for a system as complex as this one.

Implementations using PyTorch and TensorFlow are a work in progress.
