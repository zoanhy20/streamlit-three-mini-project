# streamlit-three-mini-project

## Project 1: Word Correction Using Levenshtein Distance

### Demo:

<div align="center">
  <img src="images/project_01_word_correction_deploy.png" alt="Project 01 Word Correction" width="600"/>
</div>

### Description:

This project applies word correction, a key aspect of natural language processing (NLP). It aims to develop applications that suggest the correct version of potentially misspelled words. Using the Levenshtein distance, which measures the minimum number of edits needed to transform one word into another, the project enhances text input accuracy by correcting misspellings.

## Project 2: Object Detection for Images using DNN Model from OpenCV

### Demo:

<div align="center">
  <img src="images/project_02_object_detection_1.png" alt="Project 02 Object Detection 1" width="600"/>
  <img src="images/project_02_object_detection_2.png" alt="Project 02 Object Detection 2" width="600"/> 
</div>

### Description:

This project focuses on Object Detection, a critical application of image processing aimed at identifying objects within an image. Using the DNN module from the OpenCV library, users can upload an input image, and the model will detect and return bounding boxes with the coordinates of detected objects.

## Project 3: Build Chatbot from HubChat

### Demo:

<div align="center">
  <img src="images/project_03_chatbot_deploy.png" alt="Project 01 Word Correction" width="800"/>
</div>

### Description:

This project focuses on developing a simple chatbot application using the Hugging Face library and Streamlit. Chatbots have seen significant development in recent years, primarily focusing on large language models capable of interacting effectively with user requests. The project involves creating a user-friendly interface where users can interact with the chatbot.

## Set-up for running Project

### Create conda environment and install all requir

```bash
$ conda create -n <env_name> -y python=3.11
$ conda activate <env_name>
$ pip3 install -r requirements.txt
```

### Run project

```bash
$ streamlit run ./<project_folder_name>/app.py
```

### Warning

If you want to chat with the chatbot in **Project 3: Chatbot**, you need to register an account on [Hugging Face](https://huggingface.co/) and enter the correct **username** and **password** to use it.