# Introduction:
Welcome to the pyGCS wiki!

pyGCS is an open source project for multiple quadcopter ground control station mainly written in Python, which will communicate multiple quadcopters to exchange real time data or mission or other data fields.

On the quadcopters, flight controllers with iNav firmware are used, while XBee is the only communication way for the whole flight process. By now, the connection structure is star structure, but XBees have the capability to form mesh or other structures.

Currently, this project is still under construction and the focus point will be successfully running on macOS, iOS systems. But it has the possibility to run on Linux or Windows systems in the future. I am sure I will do it because the start point is to develop a cross-platform ground control station.

# Features already implemented:
    1. Upload missions
    2. Check multiple quadcopter status
    3. Load Google Static Maps
    4. Mouse click on map to create waypoints
    5. iPhone Joystick App for single quadcopter control
    6. iPad GCS App mainly for quadcopter position monitoring
    7. Load missions from file
    8. Save missions to file

# Features to be implemented:
    1. Edit waypoints by dragging points on the map
    2. More features

# Sample:
Screenshot: 
![alt text](https://github.com/liutairan/pyGCS/blob/dev/dev/Sample-Figures/Snip20170309_1.png "Sample image")
