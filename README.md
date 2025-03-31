# Gen AI Storyteller

## Overview

The **Gen AI Storyteller** is a fine-tuned **GPT-2 Medium** model designed to generate creative stories based on user inputs such as **genre, character name, setting, and plot twist**. By leveraging a **dataset of 31,000 children's stories from Hugging Face**, the model has been optimized using **Parameter-Efficient Fine-Tuning (PEFT)** techniques. A user-friendly web interface built with **Flask and HTML/CSS** allows users to interactively create unique and engaging stories.

## Features

- **Fine-Tuned GPT-2 Model**: Adapted for storytelling using a large dataset of children's stories.
- **Customizable Inputs**: Users can define the genre, character names, and settings.
- **Prompt Engineering**: Ensures coherence and alignment with user preferences.
- **Locally Hosted Web Application**: Built with Flask, HTML, and CSS for seamless interaction.
- **Evaluation Metrics**: Readability and quality are assessed using:
  - **Flesch-Kincaid Index**
  - **Gunning Fog Index**
  - **Perplexity**
  - **Automated Readability Index**  


### Prerequisites
Ensure you have **Python 3.8+** installed along with the following dependencies:

```bash
pip install torch transformers flask numpy scikit-learn sentence-transformers
