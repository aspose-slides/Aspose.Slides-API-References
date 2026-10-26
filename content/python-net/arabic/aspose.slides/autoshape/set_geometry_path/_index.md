---
title: set_geometry_path method
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/autoshape/set_geometry_path/
weight: 90
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
يُحدّث هندسة الشكل من كائن [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). يجب أن تكون الإحداثيات نسبية إلى الزاوية اليسرى العليا للشكل.
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
| **RuntimeError(Proxy error(ArgumentException))** | لم يُعثر على مسار |
| **RuntimeError(Proxy error(ArgumentException))** | تم العثور على مسار فارغ |



### انظر أيضًا
* فئة [`AutoShape`](/slides/python-net/ar/aspose.slides/autoshape)
* فئة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)