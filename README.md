# Smart Frame AI

**Smart Frame AI** is a web application that leverages advanced AI technology to analyze images captured from a camera and generate content based on them. This application uses the Google Gemini API for content generation and Markdown for rendering the responses.

## Features

- **Real-time Image Capture**: Uses the device's back camera to capture images at regular intervals.
- **Content Generation**: Sends captured images to the Google Gemini API for content analysis and generation.
- **Markdown Rendering**: Displays the AI-generated content in a formatted Markdown view.
- **Professional Design**: Features a clean, user-friendly interface with modern design elements.

## Installation

### Prerequisites

- Python 3.8 or later
- Flask
- Requests
- Markdown

### Setup

1. **Clone the repository:**

    ```bash
    git clone https://github.com/shahram8708/smart-frame.git
    cd smart-frame
    ```

2. **Create and activate a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Flask application:**

    ```bash
    python app.py
    ```

    The application will start on `http://127.0.0.1:5000/`.

## Usage

1. Open the application in your web browser.
2. Allow access to your device's camera.
3. The application will automatically start capturing images and sending them to the AI service.
4. The generated content will be displayed on the webpage.

## API Integration

The application communicates with the Google Gemini API to generate content from images. Ensure you have a valid API key and replace `API_KEY` in `app.py` with your key.

## Project Structure

- `app.py`: The main Flask application script.
- `templates/index.html`: The HTML template for the web interface.
- `static/style.css`: The CSS file for styling the web page.
- `requirements.txt`: Lists the Python dependencies.

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request. Ensure that your code follows the existing style and includes tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**Smart Frame AI** is developed and maintained by [Shah Ram](https://github.com/shahram8708).
