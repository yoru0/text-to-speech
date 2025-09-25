# Text to Speech

Notebook demonstrating speech-to-text inference with Wav2Vec2 and text-to-speech synthesis using gTTS.

## Contents
- `main.ipynb` – end-to-end workflow for automatic speech recognition and speech synthesis.

## Getting Started
1. Install Python 3.9 or newer.
2. (Optional) create and activate a virtual environment.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch Jupyter and open the notebook:
   ```bash
   jupyter notebook main.ipynb
   ```

## Usage
### Speech to Text
- Place the audio file you want to transcribe at `test.wav`, sampled at 16 kHz (or update the path in the notebook).
- Run the "Speech To Text" section to load the Wav2Vec2 model, tokenize the waveform, and decode the predicted transcript.

### Text to Speech
- Update the example text string and execute the "Text To Speech" cells to synthesise audio with gTTS.
- The resulting MP3 file is written to the working directory (default `english.mp3`).
