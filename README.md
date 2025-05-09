# speed-based-search-engine
You've uploaded the file: **`speech based search engine.py`**, which implements a voice-activated web search tool. Here's the `README.md` tailored specifically for this script:

---

# 🗣️ Speech-Based Search Engine

A simple Python script that allows users to perform Google searches using their voice. The script captures audio from the microphone, converts it to text using Google’s Speech Recognition API, and opens the search results in the default web browser.

## 📦 Features

* Voice recognition for spoken search queries
* Speech feedback using text-to-speech
* Automatic Google search based on recognized voice input

## 🛠️ Installation

Install the required libraries:

```bash
pip install SpeechRecognition pyttsx3 pyaudio
```

> **Note:**
>
> * On Windows, if you face issues with `pyaudio`, install it via a wheel from [https://www.lfd.uci.edu/\~gohlke/pythonlibs/#pyaudio](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio).
> * On Linux/macOS, install using `brew install portaudio` or `apt install portaudio19-dev` and then `pip install pyaudio`.

## 🚀 Usage

Run the script:

```bash
python "speech based search engine.py"
```

Speak clearly when prompted. The program will transcribe your speech and open a Google search for the query.

## 📁 File Structure

* `speech based search engine.py` — Main Python script containing all logic.

## 🧠 How It Works

1. Initializes a text-to-speech engine (`pyttsx3`)
2. Listens for voice input via microphone
3. Converts voice to text using Google Speech Recognition
4. Performs a Google search using the recognized text
5. Speaks the response to confirm the action



