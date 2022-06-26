# angledbox_msgs

A simple ROS package for communication of arrays of angled bounding box between [multi_tracker](https://github.com/tgieruc/multi_tracker) and [msl_raptor](https://github.com/tgieruc/msl_raptor).

The format is [center_x center_y width height angle]. The angle is given in radian and is equal to zero when the angled box is axis-aligned.
