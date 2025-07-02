# Project Explanation

This is a web-based Augmented Reality (AR) application that uses a marker to display a 3D model of a robot. It's built using the A-Frame and AR.js libraries.

## How it works:

1.  **`index.html`:** This is the main file that sets up the AR scene.
    *   It includes the necessary A-Frame and AR.js libraries.
    *   It defines a "marker" (the `patt.hiro` pattern). When your device's camera sees this marker, it will trigger the AR experience.
    *   It loads a 3D model of a robot from a URL.
    *   It places the robot on top of the marker in the AR scene.
    *   It includes custom JavaScript code (`manipulator` component) that allows you to move, rotate, and scale the robot using touch gestures on your screen.

2.  **`data/camera_para.dat`:** This file contains camera calibration parameters. This is important for accurately tracking the marker and placing the 3D model in the real world.

3.  **`data/patt.hiro`:** This is the image of the marker that the application looks for. When you point your camera at this pattern, the robot will appear.

## In short:

You can open the `index.html` file in a web browser on a device with a camera (like a smartphone or tablet). Then, you can point the camera at the "hiro" pattern, and you'll see a 3D robot appear on your screen, seemingly in the real world. You can then use your fingers to move, rotate, and scale the robot.
