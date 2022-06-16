# Gas and Anomaly Detectors
This repository holds the files to replicate the results. 
Step 0 and 1 explains how all the files from the dataset are loaded and features extracted. 
The process can take hours so files containing all the features for each experiment are also included to skip these steps. 
2 shows the results from the tree-based gas leak detector, and 3 shows the occ anomaly detector results.  

## 0. Get the Dataset
To use the datset used in this project without having to download 20GB, follow this link to create a shortcut to the folder: 

https://drive.google.com/drive/folders/1oc_4C5-dob3sHXk6yVxnxZ4JiaIx5HPx?usp=sharing

Click on the "IDMT_dataset" drop-down below the search bar in Drive and click: "Add shortcut to Drive". 

The folder should now be stored  in "My Drive". 


## 1. Preloading files
The second step is to extract information about each file based on the path to be able to group files based on environments, microphone, leak etc. 

Open the file: "file_information_retrivel.ipynb" by clicking the button below and follow the instructions to create a "wav_paths_master.csv" file that is needed later. 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1QJLe1TaPOdXvV55k4yboLGHj8_DijRRQ)

## 2. Creating and saving feature tables


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17L4cbh0ChBKd1AcEx8-NyNAnQzezaSVC#scrollTo=DRqeCOvk6gOD)


## 3. Gas leak detection
The file below is used to execute the four gas leak detection experiments (E1-E4). 
First the features created in step 1 are loaded, before running the cells for the relevant experiment.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1dOWtMDvH176oK6659c7aSGjpkiH1JCWZ#scrollTo=1MDNp_w6jHd1)


## 4. OCC anomaly detection
The file below is used to execute the OCC anomaly detection experiments. 
First the features created in step 1 are loaded, before running the cells for the relevant experiment.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1u79AP-jrv9ObgXY604Aae-O7rS0nRKvd#scrollTo=hC7Y0q9qwsEc)

