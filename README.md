# Surface modeling and intuitive deformations

Three.js based 3D mesh deformation sandbox.

<p align="center">
    <img src="arap.gif" width="85%" height="85%"/>
</p>

App available at: https://arap-x.herokuapp.com

Video demo available [here](https://youtu.be/DLHOiWDUmwI).

## As-Rigid-As-Possible paper implementation

The model deformations are calculated following the algorithm detailed in [1] below.

This project was developed for the *INF555 - Digital Representations and Analysis of Shapes* course at École Polytechnique. 

## How build/run locally
To easily build and run the sandbox locally just run the following commands in the root:

```
$ docker-compose build && docker-compose up
```

The generated docker image is heroku ready!

References
----------
1. Sorkine O., Alexa M.: **As-Rigid-As-Possible Surface Modeling** (2007). *The Eurographics Association*. Available at \<http://www.igl.ethz.ch/projects/ARAP/arap_web.pdf>

2. Three.js library documentation. Available at \<https://threejs.org/docs/index.html>

3. The WebSocket interface - HTML Living Standard. Available at \<https://html.spec.whatwg.org/multipage/web-sockets.html>
