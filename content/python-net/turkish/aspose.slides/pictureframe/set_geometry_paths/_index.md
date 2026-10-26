---
title: set_geometry_paths method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/pictureframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Şekil geometrisini [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) dizisinden günceller. Koordinatlar, şeklin sol üst köşesine göre göreceli olmalıdır. Şeklin tipini ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir.

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Array geometry paths |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | No path found |
| **RuntimeError(Proxy error(ArgumentException))** | Empty path |

### Ayrıca Bakınız
* sınıf [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath)
* sınıf [`PictureFrame`](/slides/python-net/tr/aspose.slides/pictureframe)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)