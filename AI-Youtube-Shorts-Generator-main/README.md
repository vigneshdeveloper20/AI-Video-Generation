AI YouTube Shorts Generator

An AI-powered tool that automatically creates engaging YouTube Shorts from long videos. It extracts highlights, adds subtitles, and converts videos to a vertical 9:16 format using AI.

Features

🎬 Works with YouTube links and local videos

🎤 Fast Whisper-based speech transcription

🤖 AI selects the best highlight automatically

📝 Auto subtitles with styled captions

🎯 Smart face/screen cropping

📱 Vertical video for Shorts, Reels & TikTok

⚙️ CLI-based and automation friendly

Tech Stack

Python 3.10+

Whisper (GPU supported)

OpenAI (GPT models)

FFmpeg

ImageMagick

Installation
git clone https://github.com/vigneshdeveloper20/AI-Video-Generation-Projects.git
cd AI-Video-Generation-Projects
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt


Create .env file:

OPENAI_API=your_openai_api_key

Usage
./run.sh <youtube_url_or_video_file>

Output

Auto-generated vertical short video

Subtitles burned into video

Clean filenames with session IDs