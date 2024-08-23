# Prompt Enhancer  

This project provides a simple web-based tool for improving prompts. It uses the Groq API to generate improved prompts and responses.

## Features

- Input field for entering an original prompt
- Automatic generation of an improved prompt
- Side-by-side display of responses to both the original and improved prompts
- Easy-to-use interface with real-time results

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have a Groq API key. You can obtain one by signing up at [Groq's website](https://www.groq.com/).
- You have a modern web browser that supports JavaScript.

## Setup and Usage

1. Clone this repository or download the HTML file.

2. Open the HTML file in a text editor.

3. Replace the `API_KEY` constant in the JavaScript section with your actual Groq API key:

   ```javascript
   const API_KEY = 'your_actual_api_key_here';
   ```

4. Save the file and open it in a web browser.

5. Enter your original prompt in the text area.

6. Click the "Compare Prompts" button to see the improved prompt and the responses.

## Acknowledgements

- This project uses the [Groq API](https://www.groq.com/) for generating improved prompts and responses.
- [Axios](https://github.com/axios/axios) is used for making HTTP requests.

