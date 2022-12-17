README FOR POSE DETECTION.

// Libraries \\
mediapipe (For human Body detection)
cv2 (For traversing through the frames and showing the output)
numpy (Mostly used for angle calculation)
time (To create the timer)

// Brief Info \\
Detect human and calculated the angle between the knee (Closest knee) using the library mediapipe and used time library to calculate
time of each rep such that each rep lasts at least 8 seconds and if not, it'll display a feedback saying "You need to hold the position for 
more than 8 seconds".

// STEPS \\
1) Importing all above mentioned libraries and using OPENCV to read individual frames from the provided video and display it when
   running the code.
2) Work on each frame to detect the human body using mediapipe.
3) Detecting the closest knee (Using the marks that are mentioned for each part of the body and using the Z-axis to measure which leg is
   closer) and calculating the knee angle and if it more than less than 140 degrees, then the timer will start (Display on the screen),
   indicating that the yoga has begun and the program and begin measuring.
4) Once the person goes back to the original position (180 degree), the timer will stop.

// Submitted by - Naivedya Khare \\
