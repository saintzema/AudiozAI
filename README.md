# AudiozAI
A local based windows AI voice synthesis solution and text to speech solution.

Introduction
AudiozAI is a Windows-based text-to-speech and voice transformation application. It operates entirely on-device using models optimized through Qualcomm AI Hub for Snapdragon processors, ensuring enhanced performance, lower latency, and guaranteed data privacy. Users can generate natural-sounding voices from text, clone custom voices, and transform existing audio into any of the available or cloned voices—all without relying on cloud services.

Prerequisite
Python 3.11
Ensure you have Python 3.11 installed on your system.
Node.js and npm
Required for installing and managing certain frontend or build dependencies.
You can download Node.js from [nodejs.org](https://nodejs.org/).
Installation
Download/Clone the AudioNova repository onto your Windows machine.
Open the project folder in your file explorer.
Create a checkpoints folder (./checkpoints/) in the installation directory. Manually download the vallex-checkpoint.pt file from [here](https://huggingface.co/Plachta/VALL-E-X/resolve/main/vallex-checkpoint.pt) and put it in the checkpoints folder.
Double-click on the run.bat file to launch the application.
This script handles initializing necessary services and launching the user interface.
Using the Application
Once the application is running, select either:
Voice Generation to input text and generate/cloned voice.
Voice Changing to upload or record audio and transform it into another voice.
