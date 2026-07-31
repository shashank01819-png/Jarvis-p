# BuddyAI 🎙️

BuddyAI is a Python-based desktop voice assistant that listens, speaks, and helps you manage tasks.  
It features a minimal GUI, speech recognition, text-to-speech, reminders, and simple automation.

---

## ✨ Features
- 🎤 **Voice Recognition**: Uses Google Speech Recognition via `speech_recognition`
- 🗣️ **Text-to-Speech**: Powered by `edge-tts` with natural voices
- 🖥️ **GUI Widget**: Floating assistant bubble built with `tkinter`
- ⏰ **Reminders & Tasks**: Save, list, and track current tasks
- 🌐 **Web Search**: Quick answers via DuckDuckGo API
- ☁️ **Weather Updates**: Fetches live weather from wttr.in
- 📂 **File & App Control**: Open folders, apps, and close processes
- 🎶 **Music Playback**: Integrates with local music folder
- 🔊 **Adjustable Voice**: Control speed and volume dynamically

---

## 🛠️ Requirements
- Python 3.12+
- Libraries:  
  `speech_recognition`, `edge-tts`, `pygame`, `requests`, `tkinter`

Install dependencies:
```bash
pip install speechrecognition edge-tts pygame requests
