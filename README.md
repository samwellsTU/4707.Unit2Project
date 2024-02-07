
# Unit 2 Project: Musical Math

## Overview
In this project, you will create a web application that performs various musical math conversions. You will define a JavaScript module named `MusicTools.js` containing functions for converting MIDI pitch to frequency, frequency to MIDI pitch, dBFS to linear amplitude, and linear amplitude to dBFS. Your application will also include a user interface in `index.html` with buttons and input boxes to display the results of these conversions.

## Objectives
- Understand and implement JavaScript modules.
- Practice using mathematical formulas in programming.
- Interact with the HTML DOM to display data dynamically.

## Requirements

### 1. MusicTools.js Module
Create a module `MusicTools.js` with the following functions:
- `midiPitchToFrequency(midiPitch)`: Converts MIDI pitch to frequency.
- `frequencyToMidiPitch(frequency)`: Converts frequency to MIDI pitch.
- `dbfsToLinearAmplitude(dbfs)`: Converts dBFS to linear amplitude.
- `linearAmplitudeTodBFS(linear)`: Converts linear amplitude to dBFS.


### 1. MIDI Pitch to Frequency Conversion

To convert a MIDI pitch number to its corresponding frequency in hertz, use the formula:

\[ \text{Frequency (Hz)} = 440 \times 2^{\left(\frac{\text{MIDI Pitch} - 69}{12}\right)} \]

### 2. Frequency to MIDI Pitch Conversion

To convert a frequency in hertz to the closest MIDI pitch number, use the formula:

\[ \text{MIDI Pitch} = 69 + 12 \times \log_2\left(\frac{\text{Frequency}}{440}\right) \]

### 3. dBFS to Linear Amplitude Conversion

To convert decibels full scale (dBFS) to linear amplitude, use the formula:

\[ \text{Linear Amplitude} = 10^{\left(\frac{\text{dBFS}}{20}\right)} \]

### 4. Linear Amplitude to dBFS Conversion

To convert linear amplitude to decibels full scale (dBFS), use the formula:

\[ \text{dBFS} = 20 \times \log_{10}\left(\text{Linear Amplitude}\right) \]


### 2. User Interface
Your `index.html` file will contain input boxes for users to enter values and buttons to trigger conversions. The results should be displayed on the page.

### 3. Script.js
Implement event listeners and interaction logic in `script.js`. This script should import functions from `MusicTools.js` and use them to calculate and display the conversion results based on user input.

## Setup
1. Fork this repository to get started.
2. Create the `MusicTools.js` module and implement the required functions.
3. Write the `script.js` to handle user interactions and display the results.
4. Test your application thoroughly to ensure accuracy and usability.

## Submission
Submit your project by pushing your changes to your forked repository. Ensure that your final submission includes the `MusicTools.js` and `script.js` files, along with any modifications you've made to `index.html`.

Good luck, and have fun with the project!
