# ML Internship 

# Image Classifier for Cats and Dogs

This repository contains a machine learning project that implements an image classifier capable of distinguishing between images of cats and dogs. The classifier is built using the Python programming language and popular libraries like scikit-learn, streamlit, and pyngrok.

## Project Overview

The goal of this project is to develop an image classifier that can accurately identify whether an input image contains a cat or a dog. The project involves several steps, including data collection, preprocessing, model training, and building a user-friendly interface for making predictions.

## Contents

- `Minor_Project.ipynb`: This Jupyter Notebook contains the entire codebase of the project. It covers data collection using Bing Image Downloader, data preprocessing, model training using Support Vector Machines (SVM), and building a Streamlit web application for image classification.

- `app.py`: This Python script implements the Streamlit web application. It allows users to upload an image and obtain predictions about whether the image contains a cat or a dog. The model's prediction probabilities for both classes are also displayed.

- `img_model.p`: This is a pickle file that stores the trained SVM model. It is loaded by the Streamlit application for making predictions.

## How to Use

1. Clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/your-username/Minor-Project.git
   ```

2. Open the Jupyter Notebook `Minor_Project.ipynb` to explore the code and understand the project's implementation.

3. Install the required libraries using the following commands:

   ```bash
   pip install bing_image_downloader
   pip install streamlit
   pip install pyngrok
   ```

4. Run the Streamlit application using the following command:

   ```bash
   streamlit run app.py
   ```

   This will launch a web application where you can upload an image and receive predictions about whether it contains a cat or a dog.

## Sample Images

For testing the application, you can use the following sample images:

- [Cat Image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSfx__RoRYzLDgXDiJxYGxLihJC4zoqV3V0xg&usqp=CAU.jpg)
- [Dog Image](https://specials-images.forbesimg.com/imageserve/6082931ef598a85b055afe77/960x0.jpg?cropX1=0&cropX2=3475&cropY1=182&cropY2=2137.jpg)

## Acknowledgments

This project is created by Pranay as a minor project. It utilizes various open-source libraries and resources, including Bing Image Downloader, scikit-learn, and Streamlit.

Feel free to contribute, provide suggestions, and use this project for learning and experimenting with image classification techniques!




