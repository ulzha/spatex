# spatex

The regex `\d+` matches numbers in text:
The spatex `c` matches circles in an image:

Spatexes are deterministic and based on explicitly implemented and debuggable rules, unlike neural network based/ML computer vision technology.

Ships in two versions:
* a C++ library, for resource-constrained environments like robot controllers, SOCs, Raspberry Pis
* a container image, for workstation and server environments, rich with contributed modules, which may come in various programming languages, making good use of existing libraries out there.

Support for common 2d and 3d inputs (images, point clouds) makes it directly useful things like image analysis as well as robot motion planning.
