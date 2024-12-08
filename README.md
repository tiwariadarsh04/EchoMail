# Voice-Based Email System for the Visually Impaired

A Django-based web application that provides an accessible email interface for visually impaired users through voice commands and text-to-speech feedback.

## Features

- **Voice Commands**: Control the entire application using voice commands
- **Text-to-Speech**: Email content and navigation options are read aloud
- **Accessible Interface**: High-contrast, screen-reader friendly design
- **Core Email Functions**:
  - Compose and send emails
  - Read inbox messages
  - Access sent emails
  - Manage trash folder
  - Search emails

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Voice-Based-Email.git
cd Voice-Based-Email
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Run database migrations:
```bash
cd voice_based_email/mysite
python manage.py migrate
```

4. Start the development server:
```bash
python manage.py runserver
```

5. Access the application at: `http://127.0.0.1:8000`

## Voice Commands

- "Compose" - Create a new email
- "Inbox" - Check received emails
- "Sent" - View sent emails
- "Trash" - Access deleted emails
- "Back" - Return to previous page
- "Logout" - Exit the application

## Dependencies

- Django
- SpeechRecognition
- PyAudio
- gTTS (Google Text-to-Speech)
- Pygame

## System Requirements

- Python 3.8 or higher
- Microphone for voice input
- Speakers for audio output
- Internet connection for speech recognition and text-to-speech

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Google Speech Recognition API
- Google Text-to-Speech Service
- Django Framework
- Contributors and testers from the visually impaired community
