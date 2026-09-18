---
title: set_geometry_path method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/connector/set_geometry_path/
weight: 90
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
[`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) nesnesinden şekil geometrisini günceller. Koordinatlar sol
             üst köşesine göre relatif olmalıdır.
             Şeklin tipini ([`GeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir.


```python
def set_geometry_path(self, geometry_path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) | Geometri yolu |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Yol bulunamadı |
| **RuntimeError(Proxy error(ArgumentException))** | Boş yol bulundu |

### Ayrıca bakınız
* sınıf [`Connector`](/slides/python-net/tr/aspose.slides/connector)
* sınıf [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)