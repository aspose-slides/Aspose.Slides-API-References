---
title: set_geometry_paths method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/autoshape/set_geometry_paths/
weight: 100
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
يقوم بتحديث هندسة الشكل من مصفوفة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبة إلى الزاوية اليسرى العليا للشكل. يغير نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | مسارات هندسة المصفوفة |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | لم يتم العثور على مسار |
| **RuntimeError(Proxy error(ArgumentException))** | مسار فارغ |

### انظر أيضًا
* فئة [`AutoShape`](/slides/python-net/ar/aspose.slides/autoshape)
* فئة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)