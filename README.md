# Hand Gesture recognition with confirmation sound

## A fully functional flask application for Hand Gesture recognition for performing mouse and keyboard actions

This project uses dynamic gestures and static gestures for identifying hand gesture in real time using webcam, and maps the gestures to control functionalities of daily used applications (Facebook, Gmail, Youtube etc.)

## 📌 Features

- Real-time hand gesture recognition
- pre-trained model for accurate hand gesture calssification. LSTM for dynamic gesture, SVM for static gesture.
- Integration of the trained models with flask application. 
- Text-To-Speech framework "pyttsx3" plays which gesture has been performed. 

## 📂 Project Structure

- model/ #trained model files
- utils/ #utility scripts
- main.py #main script of UI-based flask application
- requirements.txt #python dependencies
- README.md #project documentation

## ⚙️ Installation
1. #####----clone the repository
2. python -m venv <environment_name>
   source <environment_name>/bin/activate
3. pip install -r requirements.txt

# make sure python version does not exceed 3.10, otherwise there will some version conflict with mediapipe and protobuf. 3.9 will be ideal.

## Run the application
python main.py