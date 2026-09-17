---
title: set_geometry_path method
second_title: مرجع API لـ Aspose.Slides بايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/pictureframe/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
يقوم بتحديث هندسة الشكل من كائن [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى اليسار
             الزاوية العليا للشكل.
             يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath) | مسار الهندسة |

### الاستثناءات

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | لم يتم العثور على مسار |
| **RuntimeError(Proxy error(ArgumentException))** | تم العثور على مسار فارغ |

### انظر أيضًا
* فئة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath)
* فئة [`PictureFrame`](/slides/python-net/ar/aspose.slides/pictureframe)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)