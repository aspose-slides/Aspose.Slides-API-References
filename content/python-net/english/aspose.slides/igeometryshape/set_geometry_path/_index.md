---
title: set_geometry_path method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/igeometryshape/set_geometry_path/
weight: 70
---


## set_geometry_path {#igeometrypath}
Updates shape geometry from [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath) object. Coordinates must be relative to the left
             top corner of the shape.
             Changes the type of the shape ([`IGeometryShape.shape_type`](/slides/python-net/aspose.slides/igeometryshape#shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/aspose.slides/shapetype#CUSTOM).


```python
def set_geometry_path(self, geometry_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath) | Geometry path |

## Exceptions

| Exception | Description |
| :- | :- |
| **System.ArgumentException** | No path found |
| **System.ArgumentException** | Empty path found |



### See Also
* class [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath)
* class [`IGeometryShape`](/slides/python-net/aspose.slides/igeometryshape)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
