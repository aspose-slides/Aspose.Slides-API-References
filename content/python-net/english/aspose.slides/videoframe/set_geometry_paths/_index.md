---
title: set_geometry_paths method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/videoframe/set_geometry_paths/
weight: 90
---


## set_geometry_paths {#listigeometrypath}
Updates shape geometry from array of [`IGeometryPath`](/slides/python-net/aspose.slides/igeometrypath). Coordinates must be relative to the left
             top corner of the shape.
             Changes the type of the shape ([`GeometryShape.shape_type`](/slides/python-net/aspose.slides/geometryshape#shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/aspose.slides/shapetype#CUSTOM).


```python
def set_geometry_paths(self, geometry_paths):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| geometry_paths | List[IGeometryPath] | Array geometry paths |

## Exceptions

| Exception | Description |
| :- | :- |
| .NET type System.ArgumentException | No path found |
| .NET type System.ArgumentException | Empty path |



