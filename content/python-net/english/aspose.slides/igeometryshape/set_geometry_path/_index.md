---
title: set_geometry_path method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docS
url: /aspose.slides/igeometryshape/set_geometry_path/
weight: 50
---


## set_geometry_path {#IGeometryPath}
Updates shape geometry from [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath) object. Coordinates must be relative to the left
             top corner of the shape.
             Changes the type of the shape ([`IGeometryShape.shape_type`](/slides/python-net/aspose.slides/igeometryshape#shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/aspose.slides/shapetype#CUSTOM).


```python
def set_geometry_path(self, geometry_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| geometry_path | IGeometryPath | Geometry path |

## Exceptions

| Exception | Description |
| :- | :- |
| .NET type System.ArgumentException | No path found |
| .NET type System.ArgumentException | Empty path found |



