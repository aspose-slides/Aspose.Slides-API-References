---
title: set_geometry_paths method
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/geometryshape/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
يقوم بتحديث هندسة الشكل من مصفوفة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبة إلى الزاوية العليا اليسرى للشكل.
يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| معامل | نوع | وصف |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Array geometry paths |

### استثناءات

| استثناء | وصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | No path found |
| **RuntimeError(Proxy error(ArgumentException))** | Empty path |

### انظر أيضًا
* فئة [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape)
* فئة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)