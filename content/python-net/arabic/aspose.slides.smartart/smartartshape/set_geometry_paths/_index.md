---
title: set_geometry_paths method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.smartart/smartartshape/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
يقوم بتحديث هندسة الشكل من مصفوفة من [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية العليا اليسرى للشكل.
يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| المعلمة | النوع | الوصف |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | مصفوفة مسارات الهندسة |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | لم يتم العثور على مسار |
| **RuntimeError(Proxy error(ArgumentException))** | مسار فارغ |

### انظر أيضًا
* الفئة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath)
* الفئة [`SmartArtShape`](/slides/python-net/ar/aspose.slides.smartart/smartartshape)
* الوحدة [`aspose.slides.smartart`](/slides/python-net/ar/aspose.slides.smartart)
* المكتبة [`Aspose.Slides`](/slides/python-net)