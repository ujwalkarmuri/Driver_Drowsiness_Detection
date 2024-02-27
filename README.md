# Driver_Drowsiness_Detection
Driver drowsiness detection is a project built using Dlib and OpenCV with Python as a backend language.
# Overview
This project aims to detect driver drowsiness in real-time using computer vision techniques. The system analyzes a stream of images from a camera mounted inside a vehicle to monitor the driver's facial features and detect signs of drowsiness or fatigue. When drowsiness is detected, appropriate alerts are triggered to prompt the driver to stay alert and focused on the road.

# Features
Real-time monitoring of driver's facial features.
Detection of common signs of drowsiness such as closed eyes, yawning, and nodding.
Configurable alert mechanisms including audio alerts, visual alerts, and haptic feedback.
Integration with existing vehicle systems for enhanced safety.
Lightweight and efficient implementation suitable for resource-constrained environments.
<h3>Logic of project</h3>
The project includes direct working with the 68 facial landmark detector and also the face detector of the Dlib library.
The 68 facial landmark detector is a robustly trained efficient detector which detects the points on the human face using which 
we determine whether the eyes are open or they are closed.</br></br>
<b>The 68-landmark detector data (.dat) file can be found <a href="http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2"> By clicking here</a></B>
