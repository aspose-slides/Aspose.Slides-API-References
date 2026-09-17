---
title: set_geometry_paths method
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/pictureframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
يحدّث هندسة الشكل من مصفوفة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل. يغيّر نوع الشكل ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) إلى [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | مسارات هندسة المصفوفة |

### الاستثناءات

| استثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | لم يتم العثور على مسار |
| **RuntimeError(Proxy error(ArgumentException))** | مسار فارغ |



### أنظر أيضًا
* الفئة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath)
* الفئة [`PictureFrame`](/slides/python-net/ar/aspose.slides/pictureframe)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)