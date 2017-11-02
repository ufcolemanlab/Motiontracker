## Mouse Motion Tracking
This repository contains a python script to track the motion based on a cropped region of interest. It uses the pixel difference of a reference frame to determine if there is motion. If there is a pixel difference, a contour is drawn based on the difference. If the contour is large enough, motion is recorded. 

## Usage
* The Python progress bar may need to be downloaded and can be downloaded here [https://pypi.python.org/pypi/progress]
```
python Motiontracker.py
```
* Select the .mp4 file
* Once the desired chamber to track is empty press 'P' to pause
* Press 'M' to select the chamber
* Press 'Q' once finished.
* Motion in the chamber will be tracked

## New Features
* Progress bar now tracks and shows number of frames processed 

## Future Development 
* Add ability to track a second chamber (COMPLETE)
* Calculate time spent in each chamber
