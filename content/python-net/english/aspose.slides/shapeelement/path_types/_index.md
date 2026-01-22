---
title: path_types property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapeelement/path_types/
weight: 40
---


## path_types property
Gets an array of byte values that specify the type of each point in the element's path. 
            
**0**  Indicates that the point is the start of a figure.


**1**  Indicates that the point is one of the two endpoints of a line.


**3**  Indicates that the point is an endpoint or control point of a cubic Bezier spline.


**7**  Masks all bits except for the three low-order bits, which indicate the point type.


**16**  Specifies that the corresponding segment is dashed.


**32**  Specifies that the point is a marker.


**128**  Specifies that the point is the last point in a closed subpath (figure).


**129**  Indicates a data point that is both a line segment endpoint and the last point of a closed subpath.

### Definition:
```python
@property
def path_types(self):
    ...
```


### See Also
* class [`ShapeElement`](/slides/python-net/aspose.slides/shapeelement)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

