Hi there interviewers!  

This is my submission for the GDSC interview for ML.  

I present you with 3 files, with which i have tried to achieve different things.  

The things common in all 3 is the following:  
1. Required libraries were imported
2. The dataset was loaded
3. Any required pre processing was performed
4. The data was split into inputs and outputs
5. It was further split in train and test data
6. From here the models were trained with the auc roc loss metric and accuracy graphs were plotted

The first file '1.ipynb' is using pre-trained models fitted with the test data and does not include any measures for the class imbalance.  

The second file '2.ipynb' follows the first file and uses SMOTE to create artificial data for reducing the class imbalance by interpolating new data from two already existing points.  

The third file '3.ipynb' diverges from the other two and focuses on making a custom model with a input layer, 3 hidden layers and an output layer 
