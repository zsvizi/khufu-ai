# Khufu.AI

## Description
This repository contains sample code for the framework called **Khufu.AI**, which provides an automated solution for
- processing CVs from loading to exporting to a standardized database
- ranking applicants for a position

``sample_recognition.ipynb`` contains a sample code for recognition, which is the first step of CV processing.
This implementation uses *Google Cloud Platform* (GCP), which provides state-of-the-art text recognition in its 
Vision API service. Further steps of the algorithm (reconstruction, interpretation, ranking) are not included here.

## Installation
Use `requirements.txt` to install dependencies for this project, then run `jupyter notebook` from command line.
Other requirements:
- Python 3.6+
- GCP account with a project, where Vision API is enabled, see 
[GCP Vision API](https://cloud.google.com/vision/docs/before-you-begin). You can copy the key file to `./key` folder.
