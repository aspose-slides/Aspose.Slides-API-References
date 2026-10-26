---
title: set_geometry_path method
second_title: مرجع API Aspose.Slides للغة بايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/videoframe/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
يقوم بتحديث هندسة الشكل من كائن [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبة إلى الزاوية اليسرى العليا للشكل.
             يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath) | مسار الهندسة |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | لم يتم العثور على مسار |
| **RuntimeError(Proxy error(ArgumentException))** | تم العثور على مسار فارغ |

### انظر أيضًا
* فئة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath)
* فئة [`VideoFrame`](/slides/python-net/ar/aspose.slides/videoframe)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)