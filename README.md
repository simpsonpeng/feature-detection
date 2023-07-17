# feature-detection
We have published a .exe program for point cloud feature point detection
Run:
Input: Point cloud with its filtered normal (in a PLY format)
Output:
feature_points.ply

Parameter explanation:
input neighborhood size: Determine a neighborhood for initial feature point detection.

input k_i^n: A parameter that reduces the impact of noise.

input the number of reserved points: Determine the number of points to be retained.

Note:
Only support the point cloud with “PLY” format
Some parameters are hardly-coded in our code, although they occur in our paper.
