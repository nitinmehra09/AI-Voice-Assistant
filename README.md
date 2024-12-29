# AI Voice Assistant

An AI-powered voice assistant built using Python and Livekit that enables seamless voice-based interactions. This project aims to provide a robust platform for integrating voice recognition, text-to-speech, and task automation features.

## Features

- **Voice Recognition**: Converts speech into text in real-time.
- **Text-to-Speech (TTS)**: Responds to user commands with natural-sounding voice output.
- **Livekit Integration**: Enables low-latency, real-time communication for voice interactions using the Livekit server.
- **Task Automation**: Supports executing various tasks like setting reminders, fetching information, and more.
- **Customizable Skills**: Easily extend the assistant’s capabilities to handle new commands and functionalities.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - SpeechRecognition (for voice input processing)
  - Pyttsx3 (for text-to-speech conversion)
  - Flask (for backend services)
- **Livekit**: For enabling real-time voice communication via a Livekit server.
- **Additional Tools**: Any other dependencies can be listed here.

## Prerequisites

Before running the project, ensure you have the following installed on your system:

- Python 3.8 or above
- pip (Python package manager)
- A Livekit server setup with valid credentials and API keys

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/ai-voice-assistant.git
   cd ai-voice-assistant
   ```

2. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Livekit:**
   Update the `.env` file with your Livekit server credentials, including the API key, secret, and server URL.

## Usage

1. **Start the Assistant:**
   Run the following command to start the application:

   ```bash
   python main.py
   ```

2. **Interact with the Assistant:**

   - Speak your commands into the microphone.
   - The assistant will process your command and respond appropriately.

## Project Structure

```
ai-voice-assistant/
|-- Ai/              # Virtual environment (venv) folder
|-- main.py          # Entry point of the application
|-- api.py           # API-related functionalities
|-- .env             # Environment variables configuration (includes Livekit credentials)
|-- requirements.txt # Dependencies for the project
```

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request with your improvements or bug fixes.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- **Livekit**: For providing real-time voice communication capabilities.
- **Python Community**: For the open-source libraries and support.
- **You**: For using and contributing to this project!

