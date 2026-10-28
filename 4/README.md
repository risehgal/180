# CS180 Project 4A

## Dependencies

Install the required packages:

python3 -m pip install numpy matplotlib scikit-image scipy

## Running

Run from the parent directory of the 4 folder:

python3 4/main.py

The following files must be inside 4:
- main.py
- building1.jpeg and building2.jpeg
- room1.jpg and room2.jpg
- cal1.jpg and cal2.jpg
- shoebox.jpg
- scale.jpg

## Instructions

For building, room, and Cal, select eight matching points in each image. Select the same features in the same order in both images.

For the shoebox and scale, select four corners in this order:
1. Top left
2. Top right
3. Bottom left
4. Bottom right

Point-selection windows close after the required number of clicks. Right-click during selection to undo the most recent point.

Close each result window using X to continue to the next step.

The building and room homography matrices print in the terminal.

## Outputs

The script creates 4/results automatically and saves:
- Four building and room correspondence images
- Nearest-neighbor and bilinear rectifications of the shoebox and scale
- Building, room, and Cal mosaics

Rectification and mosaic images are saved at the end, after closing the final Cal mosaic window. Let the script finish.

Each run requires selecting the points again. Full-resolution mosaics may take time to compute.
