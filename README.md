# SAM 2 Hand Tracking

This project leverages the Segment Anything Model (SAM) and MediaPipe to create a robust hand tracking pipeline.  It processes video frames, identifies hand regions, and generates masks for further analysis or manipulation.

## Setup Instructions

### Install Dependencies
```sh
conda create -n sam2 python=3.12
conda activate sam2
pip install -r requirements.txt
```
## Run the notebook
jupyter notebook Hand_Tracking.ipynb

## Examples

### Before Masking
![0000_readme](https://github.com/user-attachments/assets/fa2a807f-d5e5-457d-86b7-f378d28f6e2e)

### After Masking
![masked_frame_0000](https://github.com/user-attachments/assets/c51a3b5e-2dc0-4a75-8009-371e6def3913)

### Demo
[Watch Video](https://www.youtube.com/watch?v=m35EHsQ3MVw)
