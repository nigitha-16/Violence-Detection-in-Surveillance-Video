# Violence-Detection-in-Surveillance-Video
## Dataset 
Videos of length around 0.5 - 1.5 s were collected from different sources. 40 videos for each class (with and without violence). 
NOTE:Link to the dataset is not given.

## Steps
The C3D model is used for extracting video features.

Link to download the weights for C3D model https://www.kaggle.com/ekas99/c3d-sport1m-weights-keras-224/version/1

Mention the path to the folder containing the videos in the feature_extraction_violence_detection.ipynb file.Also mention the destination path to save the CSV file.

train_violence_detection.ipynb is to train the violence detection model.Specify the paths at required places

test_violence_detection.ipynb is to test the violence detection model.Specify the paths at required places


Reference :
W. Sultani, C. Chen and M. Shah, "Real-World Anomaly Detection in Surveillance Videos," 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition, Salt Lake City, UT, 2018, pp. 6479-6488, doi: 10.1109/CVPR.2018.00678.
example
