# DETR_FineTuning
This repository basically used how to use the latest state of the art detection model for fine tuning ,

facebook have released but not showed how to fine tune it for custom dataset and training for the
custom dataset

this is humble try to make it avialble for the training for custom dataset

### FOR MORE INFO
kindly refer to this link
[DETR REPO](https://github.com/facebookresearch/detr)
this is the original repo for detr and after that i have made several changes to it and
uploaded heres
for requirement also look at the file detr/requirement.txt

# LET'S START THE TRAINING

there'll be some step and i'll guide each and every step 

#### STEP : 1
First of all we need to install all the dependencies 
for required library and packages look at the file detr/requirement.txt and install all the requirements
and also git is need to be installed

#### STEP : 2
clone this repository
```
git clone https://github.com/pratikkorat26/DETR_FineTuning
```
#### STEP : 3
  * This model expect the data in the coco json format and specific directory structure as shown below 
    picture
  * and name of the json files should be 
    * for training data file name should be
      * instances_train2017.josn
    * for validation data file name should be
      * instances_val2017.josn
      
    * directory structure
      ```
      path to cloned repo/
        - data/
            -annotations/ json files
            -train2017/ images for training
            -val2017/   images for validation
      ```
      here the data folder is the same as present in this repo and for your data
      replace the your custom data and rename the files as i have mentioned above 
      
      i could have changed but i prefer to keep as it is ( name of the files)
      
      ![alt text](https://github.com/pratikkorat26/DETR_FineTuning/blob/main/Screenshot%20(20).png)
    
    * for converting annotations from xml to json
      - i have used the roboflow's scripts and some additional steps
      
#### STEP : 4
Now we are all set for the training
      
      


