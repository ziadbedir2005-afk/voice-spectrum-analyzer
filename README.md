# Voice Spectrum Analyzer

A real-time voice recording and spectral analysis tool built using GNU Octave.

## Overview

This project captures live microphone input and visualizes:

- Time-domain waveform
- Amplitude spectrum
- Phase spectrum
- Energy spectrum

An interactive GUI enables signal exploration and recording control.

---

## Features

- Real-time recording
- FFT spectral analysis
- Silence detection
- Dynamic zoom controls
- Audio saving
- Plot exporting

---

## Technologies

- GNU Octave
- Signal Processing
- FFT Analysis
- GUI Development

---

## GUI Controls

- Sampling frequency
- Recording duration
- Silence threshold
- Save location
- Display mode switching

---

## Processing Flow

Record Audio
→ Buffer Signal
→ Silence Detection
→ FFT
→ Spectrum Visualization
→ Save Output

---

## Results

Successfully visualized real-time speech frequency components and energy distributions.

Main voice energy concentrated below 4kHz.

---

## Project Structure

/voice-spectrum-analyzer
│── main.m
│── screenshots/
│── saved-audio/
└── README.md

---

## Future Work

- Noise filtering
- Spectrogram mode
- Real-time speech classification
