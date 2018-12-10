# datasets
synthetic dataset for training recommendation system model
each dataset is uniformed randomly created by the equation R = X * Y; with factor latent, k = 5. This means R has the size of n x m => X has the size of n x k and Y has the size of k x m
X, Y is in the range of (0,1) => R has the range of (0, 5)
the datasets are for training the model of recommendation system with matrix factorization approach and WALS model of tensorflow
clone the wals model from here https://cloud.google.com/solutions/machine-learning/recommendation-system-tensorflow-create-model and run it with the datasets
R5N15k_5k means 5% of R are known, the rest are missing. The same manner applys for all the rest
