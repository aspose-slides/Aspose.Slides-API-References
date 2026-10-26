---
title: set_geometry_paths method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/igeometryshape/set_geometry_paths/
weight: 80
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
يحدّث هندسة الشكل من مصفوفة من [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى اليسار
             الزاوية العلوية اليسرى للشكل.
             يغيّر نوع الشكل ([`IGeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/igeometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| المعلمة | النوع | الوصف |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | مصفوفة مسارات الهندسة |

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | لم يُعثر على مسار |
| **RuntimeError(Proxy error(ArgumentException))** | مسار فارغ |

### انظر أيضًا
* فئة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath)
* فئة [`IGeometryShape`](/slides/python-net/ar/aspose.slides/igeometryshape)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)