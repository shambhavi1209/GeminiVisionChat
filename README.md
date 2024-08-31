# GeminiVisionChat

This is a Streamlit application that allows users to interact with images by asking questions about them. The app leverages Google's Generative AI model, Gemini, to generate responses based on the provided image and prompt. The main purpose of this application is to provide a seamless experience for exploring visual content through conversational AI.

## Features

- Upload an image and ask questions about it.
- Use Google Generative AI (Gemini) to generate text responses based on the image and user input.
- View the conversation history of questions and answers.
- Simple and intuitive UI powered by Streamlit.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/gemini_talk_with_image.git
   cd gemini_talk_with_image

2. **Create a virtual environment**:

    ```bash

    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
3. **Install the dependencies**:

    ```bash
    Copy code
    pip install -r requirements.txt
4. **Set up your Google API Key**:

    Create a .env file in the project directory.

    Add your Google API key to the .env file:

    ```bash
    GOOGLE_API_KEY=your_google_api_key_here
