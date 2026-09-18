---
title: set_geometry_paths method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/geometryshape/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Şekil geometrisini [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) dizisinden günceller. Koordinatlar şeklin sol üst köşesine göre göreceli olmalıdır.
Şeklin tipini ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir.

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Geometri yolu dizisi |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Yol bulunamadı |
| **RuntimeError(Proxy error(ArgumentException))** | Boş yol |

### Ayrıca Bakınız
* sınıf [`GeometryShape`](/slides/python-net/tr/aspose.slides/geometryshape)
* sınıf [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)