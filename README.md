# Dense_Mapping_ORBSLAM2
Folk  from gaoxiang's ORBSLAM2 with point cloud mapping

#Modification
1. Copy pointcloudmapping.h and cc from gaoxiang's project, and add them to orignal ORBSLAM2. It is easy to build.
2. Add a choice to save dense map in map viewer. It is different from the real-time dense map in PCL viewer.
3. Change the folder based on timestamp to save pcd, ply, depth image and rgb image as well as trajectory.
