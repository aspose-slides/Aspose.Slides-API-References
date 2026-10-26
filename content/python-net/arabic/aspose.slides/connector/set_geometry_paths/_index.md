---
title: set_geometry_paths method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/connector/set_geometry_paths/
weight: 100
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Updates shape geometry from array of [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath). Coordinates must be relative to the left
             top corner of the shape.
             Changes the type of the shape ([`GeometryShape.shape_type`](/slides/python-net/ar/aspose.slides/geometryshape/shape_type)) to [`ShapeType.CUSTOM`](/slides/python-net/ar/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | مصفوفة مسارات الهندسة |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | لم يتم العثور على مسار |
| **RuntimeError(Proxy error(ArgumentException))** | مسار فارغ |

### انظر أيضًا
* فئة [`Connector`](/slides/python-net/ar/aspose.slides/connector)
* فئة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)