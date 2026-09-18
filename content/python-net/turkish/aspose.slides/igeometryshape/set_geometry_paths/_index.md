---
title: set_geometry_paths method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/igeometryshape/set_geometry_paths/
weight: 80
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Şekil geometrisini [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath) dizisinden günceller. Koordinatlar sol
             üst köşesine göre göreceli olmalıdır.
             Şeklin türünü ([`IGeometryShape.shape_type`](/slides/python-net/tr/aspose.slides/igeometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/tr/aspose.slides/shapetype/CUSTOM) olarak değiştirir.


```python
def set_geometry_paths(self, geometry_paths):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Dizi geometri yolları |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Yol bulunamadı |
| **RuntimeError(Proxy error(ArgumentException))** | Boş yol |



### Ayrıca Bakınız
* sınıf [`IGeometryPath`](/slides/python-net/tr/aspose.slides/igeometrypath)
* sınıf [`IGeometryShape`](/slides/python-net/tr/aspose.slides/igeometryshape)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)