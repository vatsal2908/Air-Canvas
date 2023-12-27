# Air-Canvas

It is a user interactive project based on python using OpenCV library. It allows user to draw and erase in the canvas using various hand gestures. 

# Features 

1. Hand Gesture Recognition : 
Experience the freedom of drawing directly in the virtual space. With AirCanvas, users can effortlessly express their creativity by using hand gestures to draw lines, shapes, and intricate designs.
For detect and track hand landmarks we used Mediapipe library.

2. Color Palette :
Choose from a vibrant color palette featuring blue, green, and red colour. Tailor your creations with a spectrum of colors, allowing for dynamic and visually stunning drawings.

3. Reset Button :
Correct and refine your artwork with the reset tool. Easily undo drawings to achieve the desired results, adding precision and control to the creative process.

4. Canvas :
It is the white coloured canvas on which your drawing will be reflected.

# How it Works 

Hand Tracking : It tracks your tip of index finger and will draw as you move your hand in particular direction. It recognizes hand gestures by use of mediapipe library and can be detected by webcam.

Real-time visualization : It displays both live webcam on which user is drawing and it will be reflected on white canvas.

# Setup and Usage

Requirements : Ensure Python, numpy, mediapipe and OpenCV libraries are installed with all the required dependencies. Ensure that you have a webcam.

Execution : Run the provided python script to open the Air-canvas.

Termination : You can simply close this program by pressing 'q' in the window displaying the live webcam feed.

# Contribution and Enhancement

Feel free to fork the AirCanvas repository and contribute to its evolution. Whether you aim to enhance features, modify functionalities, or experiment with new ideas, your valuable contributions are welcome to enrich the AirCanvas experience for all users.
