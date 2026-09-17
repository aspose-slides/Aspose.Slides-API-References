---
title: set_geometry_path method
second_title: Aspose.Slides ل Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/geometryshape/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
يقوم بتحديث هندسة الشكل من كائن [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية العلوية اليسرى للشكل. يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath) | Geometry path |

### استثناءات

| استثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | لم يتم العثور على مسار |
| **RuntimeError(Proxy error(ArgumentException))** | تم العثور على مسار فارغ |



### راجع أيضًا
* فئة [`GeometryShape`](/slides/python-net/ar/aspose.slides/geometryshape)
* فئة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)