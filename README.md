# Book Summary Analysis and Visualization

This repository contains a Python project for analyzing, summarizing, and visualizing a dataset of book summaries. Using a combination of **Natural Language Processing (NLP)**, **Computer Vision**, **Machine Learning**, and **Data Visualization**, this project explores book summaries, condenses their content, and transforms them into visually engaging images.

## 📋 Project Overview
The objective of this project is to:
- Clean and explore the dataset to understand patterns and insights.
- Summarize and condense book summaries using NLP techniques.
- Generate images that visually represent the condensed summaries using a text-to-image model.

## 🛠️ Key Features
- **Data Preprocessing and Exploratory Data Analysis (EDA)**: Handles missing values, extracts relevant features, and visualizes data trends.
- **NLP Summary Condensation**: Uses a transformer-based model to condense long book summaries into brief summaries.
- **Image Generation**: Converts condensed summaries into images using a text-to-image model, leveraging a stable diffusion pipeline.

## ⚙️ Requirements
To run this project, ensure the following packages are installed:
```bash
pip install torch transformers accelerate diffusers rouge
