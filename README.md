Gastrointestinal (GI) diseases account for the majority of disability-adjusted life years (DALYs) in 2016 and are regarded as one of the most distressing problems that people encounter. Annually, GI problems impact 2.8 million people and are reported to be responsible for 1.8 million fatalities. 

Considering the importance and prevalence of GI diseases worldwide, we trained an effective CNN-based multiclass classification model to classify wireless camera endoscopy (WCE) images of three GI diseases (polyps, ulcer, esophagitis) and normal colon. The ResNet50-based CNN model achieved highest average accuracy of approximately 99.80% on the training set (100% precision and approximately 99% recall) and accuracies of 99.50% and 99.16% on the validation and additional test set. 


**Package requirements:**
    a) python = 3.9 
    b) numpy
    c) pandas
    d) tensorflow=2.11.0
    e) keras = 2.11.0
    f) scikit-learn
    g) scipy
    
**Repository files: **
    a) Readme file
    b) Trained model: generated-model.h5 file 
    c) Folder named 'images' where images to be classified are to be saved
    d) Prediction program: prediction_crc.py

**Input**: Image file (image.jpg)

**Output**: Prediction file

**Execution:**
**Step 1**: Install Anaconda3-5.2 or above.

**Step 2**: Install or upgrade libraries mentioned above (python, numpy, pandas, tensorflow, keras, scikit-learn, scipy).

**Step 3**: Download and extract zipped file.

**Step 4**: 
Save the images to be predicted in "images" folder

**Step 5**: Change value of path variable in prediction_crc.py to the extracted folder and execute the script.
