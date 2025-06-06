# IOT Sauron 👁️  
**Real-Time Computer Vision Tracking with Raspberry Pi & OpenCV**

[🔗 Live Demo](https://mja266.github.io/IOTSauron/)

## Overview
IOT Sauron is a Raspberry Pi–powered computer vision system that uses OpenCV for dynamic face and color tracking. It combines real-time video streaming with precise servo control to mimic a surveillance-style camera that tracks subjects as they move across frames.

## Features
- 🎥 **Live Video Feed** accessible via web browser
- 🧠 **Face & Color Detection** using OpenCV
- 🔁 **Real-Time Servo Control** using PD controllers and PWM signals
- 🌐 **Multi-Camera Streaming** architecture
- 🖥️ **Browser-based Interface** for ease of access and monitoring

## Technologies Used
- Python  
- OpenCV  
- Raspberry Pi  
- Flask (for web streaming)  
- Servo motor + PWM  
- HTML/CSS for the frontend  

## Contributors
- Mohamed Abdalla  
- Rahul Goel  
- James Ong  

## How It Works
1. A camera connected to Raspberry Pi captures a video stream.
2. OpenCV processes each frame to detect faces or specific colors.
3. Detected objects are used to compute directional feedback.
4. Servo motors adjust the camera's orientation in real-time based on PD control logic.
5. The live stream is served to a browser-accessible page using a Flask backend.

## Demo
Visit the live deployment here:  
👉 [https://mja266.github.io/IOTSauron/](https://mja266.github.io/IOTSauron/)

## License
MIT License
