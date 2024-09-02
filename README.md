# Flet Chat App with Google AI and Dynamsoft Barcode Reader
The project demonstrates how to integrate [Gemini APIs](https://ai.google.dev/tutorials/python_quickstart) into a Flet chat app.

https://github.com/yushulx/flet-chat-app-gemini-barcode/assets/2202306/ef159de0-cdf9-48e2-91d9-3da3ce9f85a0

## Installation

```bash
pip install -r requirements.txt

```

## Getting Started
1. Get an [API key](https://makersuite.google.com/app/apikey) for Gemini in Google AI Studio and replace the value of `API_KEY` in `chatbot.py`.
    
    ```python
    genai.configure(api_key='API_KEY')
    ```

    ![Gemini API key](https://github.com/yushulx/flet-chat-app-gemini-barcode/assets/2202306/a556a3dc-622f-4de0-b3d5-9067de44a5e5)

    
3. Run the app:

    ```bash
    flet run chatbot.py
    ```
