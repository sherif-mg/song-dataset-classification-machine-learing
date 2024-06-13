# song-dataset-classification-machine-learing
SVM is a supervised learning algorithm used for classification tasks. It works by finding the optimal hyperplane that separates different classes in the feature space. For non-linearly separable data, SVM uses kernel functions to map the data into a higher-dimensional space.

Dataset Description
Song Dataset
The dataset includes features such as tempo, key, and duration of songs. The goal is to classify songs into different genres or categories.

Features
Tempo: Speed of the song in beats per minute.
Key: Musical key of the song.
Duration: Length of the song in seconds.
Methodology
Data Preprocessing
Handling Missing Values: Impute or remove missing values.
Normalization: Scale features to a standard range.
Encoding Categorical Features: Convert categorical features into numerical values.
Training the SVM Model
Splitting the Data: Divide the dataset into training and testing sets.
Selecting the Kernel: Choose a kernel function (e.g., linear, RBF).
Training the Model: Fit the SVM model using the training set.
Hyperparameter Tuning: Optimize parameters for best performance.
Evaluation Metrics
Precision: Measures the accuracy of positive predictions.
Recall: Measures the ability to identify all relevant instances.
F1-Score: Balances precision and recall.
