---
title: set_geometry_path method
second_title: مرجع API لـ Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.smartart/smartartshape/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
يحدّث هندسة الشكل من كائن [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل. يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath) | مسار الهندسة |

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | لم يتم العثور على المسار |
| **RuntimeError(Proxy error(ArgumentException))** | تم العثور على مسار فارغ |

### انظر أيضًا
* فئة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath)
* فئة [`SmartArtShape`](/slides/python-net/ar/aspose.slides.smartart/smartartshape)
* وحدة [`aspose.slides.smartart`](/slides/python-net/ar/aspose.slides.smartart)
* مكتبة [`Aspose.Slides`](/slides/python-net)