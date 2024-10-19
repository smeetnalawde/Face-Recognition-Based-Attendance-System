# face-recognition-based-attendance-system

This repository contains the source code and resources for the **Face Recognition Based Attendance System** project. The project uses face recognition technology to track attendance in real-time.

## Project Structure

The main files included in the ZIP folder are:

1. Template Folder:  
   - This folder contains the HTML file that is used for the front-end display of the system.
   - Path: `template/`
   - File: `home.html` – This file is the main interface for the attendance system where users can view the attendance tracking dashboard.

2. Python File:  
   - The core Python script that runs the face recognition algorithm and manages the attendance data.
   - Path: In the main folder.
   - File: `attendance.py` – This file includes the logic for face detection, recognition, and attendance logging using OpenCV and face-recognition libraries.
   - Important : Make sure to update the file paths inside attendance.py to match the location where you have saved the files on your system and you need to provide the full system path in the python script.

3. Haarcascade File:  
   - This is a pre-trained classifier file for face detection using OpenCV's Haar Cascade algorithm.
   - Path: In the main folder.
   - File: `haarcascade_frontalface_default.xml` – This file helps the system detect faces from the video feed.

---

### How to Run the Project

1. Download and extract the zip file.
2. Make sure you have Python installed and all necessary dependencies ('opencv-python', 'face-recognition', etc.).
3. Run the 'attendance.py' file to start the system.
