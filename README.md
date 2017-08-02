# Project3

This is the initial commit for Project #3 - Perception Pick n Place for
Udacity Robotics NanoDegree Program.

This commit includes Python code provided by Udacity as a starter template.

The objective of the project is to enable a robotic arm to pick n place 
a specific object to be identified among a group of objects with diffeent 
shapes and colors by using common and typical point cloud functions.

The starter code performs voxel grid downsampling, pass through filtering (using
z axis interval), segmentation using RANSAC plane fitting, extraction of inliers
and outliers (to obtain subsets of the data - in this case the "table" and the
"objects" on the table), and finally the PCL Euclidean Clustering alorithm to separate
point clouds into discrete objects.

The student (me) was responsible in multiple steps to choose the correct CV2 and 
python-pcl function to use from the library, decide upon the optimal parameters, and
modify the code to meet certain additional specifications.
