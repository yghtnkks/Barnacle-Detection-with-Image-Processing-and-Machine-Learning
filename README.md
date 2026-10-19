# Barnacle Detection with Image Processing and Machine Learning

Author: Yigithan Akkus

This project aims to develop a solution for the barnacle problem. I develop a model-based method for automating the process, shortening the process and shortening the tedious process of determining tentacles by hand. 

# Approach
**1-Learning**
* Learn about opencv, masking, basics of HSV, RGB-BGR difference
**2-Creating contours**
* Using the mask provided, we create contours. When then create a binary mask of barnacle regions for training. 
**3-Training Random Forest**
*  Use the data we obtained to train a random forest classifier
**4-Testing the Classifier on Unseen Images**
# Repository 
─ README.md
├── requirements.txt
├── project.ipynb      # full walkthrough withcode, figures, and reasoning
└── data/
    ├── img1.png           
    ├── mask1.png          
    ├── masked_img1.png    
    ├── img2.png           
    ├── mask2.png          
    ├── masked_img2.png    
    ├── unseen_img1.png    
    └── unseen_img2.png    
# Requirements
Python 3.9 or higher is suggested

Place the images inside of a data folder in this repository. 
# Results, Limitations, Next Steps
Results, limitations, and next steps are discussed in project.ipynb file. 