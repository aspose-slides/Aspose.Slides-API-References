---
title: set_geometry_paths method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/igeometryshape/set_geometry_paths/
weight: 40
---


## set_geometry_paths {#listasposeslidesigeometrypath}
Updates shape geometry from array of [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath). Coordinates must be relative to the left
             top corner of the shape.
             Changes the type of the shape ([`IGeometryShape.shape_type`](/slides/python-net/aspose.slides/igeometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/aspose.slides/shapetype/CUSTOM).


```python
def set_geometry_paths(self, geometry_paths):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| geometry_paths | **List[aspose.slides.IGeometryPath]** | Array geometry paths |

### Examples

Example:

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | No path found |
| **RuntimeError(Proxy error(ArgumentException))** | Empty path |



### See Also
* class [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath)
* class [`IGeometryShape`](/slides/python-net/aspose.slides/igeometryshape)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

