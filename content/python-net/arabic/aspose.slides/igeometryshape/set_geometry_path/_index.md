---
title: set_geometry_path method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/igeometryshape/set_geometry_path/
weight: 70
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
يحدّث هندسة الشكل من كائن [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل.
             يغيّر نوع الشكل ([`IGeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/igeometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| معامل | نوع | وصف |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath) | مسار الهندسة |

### الاستثناءات

| استثناء | وصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | لم يتم العثور على مسار |
| **RuntimeError(Proxy error(ArgumentException))** | تم العثور على مسار فارغ |

### انظر أيضًا
* الفئة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath)
* الفئة [`IGeometryShape`](/slides/python-net/ar/aspose.slides/igeometryshape)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)