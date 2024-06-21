# Video Processing Script

This script processes videos by extracting frames, generating descriptions, summarizing the descriptions, generating TTS audio, and creating a final video clip with background music. It uses several Python libraries to achieve this.

## License

This project is licensed under the Zero-Clause BSD license.

## Requirements

- Python 3.x
- ffmpeg
- pydub
- transformers
- openai
- cv2
- PIL

## Setup

### Using a Virtual Environment

It is recommended to use a virtual environment to manage dependencies. Follow these steps to set up the project:

1. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install ffmpeg-python pydub transformers openai opencv-python pillow
   export OPENAI_API_KEY=your_api_key_here
   python snakeman.py
