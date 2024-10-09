Tamil-to-English Translation, Summarization, and Image Generation
This project is a multimodal AI application that translates text from Tamil to English, summarizes the translated text, and generates images based on the summarized content. The application uses state-of-the-art models from Hugging Face for each task and provides a simple, interactive user interface using Gradio.

Table of Contents
Overview
Features
Technologies Used
Installation
Usage
Project Structure
Models Used
Performance Analysis
Contributing
License
Overview
This application takes a Tamil text as input and performs the following operations:

Translates the Tamil text to English.
Summarizes the translated English text.
Generates an image based on the summarized text using a Stable Diffusion model.
The entire workflow is accessible through a user-friendly web interface powered by Gradio.

Features
Tamil-to-English Translation: Uses the Helsinki-NLP/opus-mt-mul-en model to translate Tamil input into English.
Summarization: Summarizes the translated English text using the facebook/bart-large-cnn model.
Image Generation: Generates an image from the summary using the Stable Diffusion model.
Interactive UI: Built using Gradio, providing an easy-to-use interface for users to interact with the application.
Technologies Used
Hugging Face Inference API: For translation, summarization, and image generation.
Gradio: For creating a web interface.
Python: Primary language for building the app.
requests: For making API calls to Hugging Face.
Stable Diffusion: For generating images from text.
CUDA: Optional, for leveraging GPU acceleration when available.
