# Text-classifier-using-Embedding-Layer
## AIM
To create a classifier using specialized layers for text data such as Embedding and GlobalAveragePooling1D.

## PROBLEM STATEMENT AND DATASET
The program enables us to classify the given BBC dataset into its respective areas like different categories, for example buisness, sports and tech using Deep learning techniques, which includes loading and preprocessing the data, creating the neural network model, training and evaluation its performance.
## DESIGN STEPS
## STEP 1
Unzip the zip file and load the BBC news dataset, split it into training and validation dataset.
## STEP 2:
Implement a function to convert the text into lower cases, remove the stop words and eliminate punctuation.
## STEP 3:
Create a TextVectorizer layer to tokenize and convert the dataset into sequences for model training.
## STEP 4:
Use TensorFlow's StringLookup layer to encode text labels into numerical format.
## STEP 5:
Build a model using an embedding layer, global average pooling, and dense layers for multi-class classification
## STEP 6:
Train the model for 30 epochs using the prepared training data and validate its performance on the validation set.
## STEP 7:
Evaluate the model's accuracy and loss, and plot the results to track performance over time.

## PROGRAM

### Name:

### Register Number:

Include your code(Model, compile and fit functions) here

## OUTPUT
### Loss, Accuracy Vs Iteration Plot

Include your plot here


## RESULT
