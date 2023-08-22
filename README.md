# deep_learning_challenge
Module 21 Challenge

Deep Learning Challenge - AlphabetSoup Charity Funding Prediction

# Background:
Alphabet Soup, a nonprofit foundation, seeks a predictive tool to assist in selecting funding recipients with the highest likelihood of success. Leveraging machine learning and neural networks, this project involves creating a binary classifier to predict whether Alphabet Soup-funded applicants will succeed in their ventures. The provided dataset encompasses over 34,000 organizations that have received funding, featuring columns capturing organizational metadata.

# Step 1: Preprocess the Data:
Begin by uploading the starter file to Google Colab and follow the provided instructions to preprocess the dataset. Read in the 'charity_data.csv' file to a Pandas DataFrame and identify target and feature variables. Drop the EIN and NAME columns, determine unique values for each column, and handle rare categorical variables. Encode categorical variables using 'pd.get_dummies()' and split data into features and target arrays. Scale the data using StandardScaler.

# Step 2: Compile, Train, and Evaluate the Model:
Design a neural network model using TensorFlow and Keras. Define input features and layer nodes, adding hidden layers with appropriate activation functions. Compile and train the model, implementing a callback to save weights every five epochs. Evaluate model performance using test data, calculating loss and accuracy. Save results in an HDF5 file named 'AlphabetSoupCharity.h5'.

# Step 3: Optimize the Model:
Create a new Google Colab file for optimization purposes. Preprocess the dataset and design a neural network model, adjusting for optimizations to achieve an accuracy above 75%. Explore modifications such as modifying input data, adding neurons or hidden layers, experimenting with activation functions, and adjusting epochs. Save the optimized model in 'AlphabetSoupCharity_Optimization.h5'.

# Step 4: Write a Report on the Neural Network Model:
Compose a report detailing the deep learning model's performance for Alphabet Soup. Provide an analysis overview, discuss data preprocessing, model compilation, training, and evaluation. Explain the selection of neurons, layers, and activation functions, as well as any steps taken to enhance model performance. Summarize overall results, recommend alternative models for the classification problem, and explain the rationale behind the recommendation.

# Step 5: Copy Files Into Your Repository:
After completing the analysis in Google Colab, download notebooks and place them in the Deep Learning Challenge directory in your local repository. Push the added files to GitHub for final submission.
