[![Static Badge](https://img.shields.io/badge/version-0.14-yellow)](https://github.com/uSANMA/blender-uwaba-prototype/tree/beta)
# BLENDER FILES
## INTRO
These are the blender files associated to our uWABA robot project. It is still in development.
<p align="center">
<img src="https://github.com/uSANMA/blender-uwaba-prototype/blob/beta/uWABA/docs/Model.png" width="500" align="center">
</p>

## ITEMS AND CHANGES
### ROBOT
Changes were made onto `uWABA robot` wheels, suspensions and LiDAR position that needs to be taken into account when creating `links` and `joints`.
- [ ] Create IMU object so that a link can be implemented in URDF file;
- [x] Add a fixed joint for the robot's suspension objects (i.e. small wheels frame objects);
- [x] Add joints and link to model
- [ ] Send urdf file to [ros2_ws/packages/src/uwaba_prototype_description/urdf](https://github.com/uSANMA/ros2-uwaba-prototype)
- [ ] Send meshes files to [ros2_ws/packages/src/uwaba_prototype_description/meshes](https://github.com/uSANMA/ros2-uwaba-prototype)

### LiDAR's SUPPORT
- [x] Added button, changed LiDAR position, resized battery slots.
- [ ] need to insert a slot for:
    - [ ] Antenna;
    - [ ] Screws;
    - [ ] Venting;
    - [ ] Reduce overall support volume;

## REFERENCES

All of it was possible thanks to [phobos'](https://github.com/dfki-ric/phobos/) extension. We are truly grateful for your tool and for making it open source.
