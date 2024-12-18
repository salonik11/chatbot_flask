
# Flask Chatbot with DialoGPT

This project demonstrates a simple chatbot using **Flask** and Hugging Face's `DialoGPT-medium` model.

## Features
- Web-based chatbot interface.
- Powered by the `microsoft/DialoGPT-medium` model.

## Requirements
- Python 3.8 or later
- Flask
- Transformers
- PyTorch

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Set up a virtual environment:
   ```bash
   python -m venv venv
   .\venv\Scripts\activate  # Windows
   source ./venv/bin/activate # macOS/Linux
   ```
3. Install dependencies:
   ```bash
   pip install flask transformers torch
   ```

## Usage
1. Start the Flask app:
   ```bash
   python app.py
   ```
2. Open your browser at `http://127.0.0.1:5000/` and start chatting.

## Troubleshooting
- Ensure all dependencies are installed.
- Verify internet connectivity for model downloads.
- Resolve port conflicts by changing `app.run()` to a different port.

## License
This project is licensed under the MIT License.

