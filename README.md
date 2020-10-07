# opencv-hsv-picker

# Requirements
 - Python 3
 - OpenCV

# Installation
 1. Create a virtual environment `python3 -m venv venv`
 2. Activate the virtual environment `source venv/bin/activate`
 3. Install OpenCV package `pip install opencv-python`

# Usage
 1. Activate the virtual environment if you have not done so yet `source venv/bin/activate`
 2. Run the Python script `python3 picker.py`
 3. Drag the H, S, and V sliders around to change the mask parameters.
    - For the include image `1.jpg` it is only necessary to change the `VMin` slider.
    - The resulting lower and upper HSV values are displayed in the terminal.
    - Pressing `X` in the preview GUI will **NOT** exit the application.
 4. Exit the script by pressing `Ctrl + C` in the terminal you executed it from.

