# Stereo Camera: Real-Time Depth and 3D Reconstruction

A stereo vision project built with an **HBVCAM-W202011HD V33 stereo camera**, covering image acquisition, camera calibration, stereo matching, real-time depth estimation, and dense 3D point cloud generation.

The project compares **Block Matching (BM)** and **Semi-Global Block Matching (SGBM)** for disparity estimation and reconstructs 3D points through back-projection. Object length measurement errors were below 10% in the project experiments.

## Results

![Stereo camera results: camera images, disparity maps, depth maps, and point cloud reconstruction](https://zhengfeisong.github.io/fig/stereocamera.png)

[Point cloud demo](pointcloud.mp4) · [Project report](Report.pdf) · [Personal website](https://zhengfeisong.github.io/projects.html)

## Repository Contents

- `stereo_matching/`: C++ stereo matching and point cloud visualization code, CMake configuration, and calibration files.
- `calibrationSession.mat`: MATLAB camera calibration session.
- `Report.pdf`: Project report.
- `pointcloud.mp4`: Point cloud reconstruction demonstration.

## Tools

C++17, OpenCV 4, Eigen3, Pangolin, and MATLAB.
