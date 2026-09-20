---
title: set_geometry_path method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/igeometryshape/set_geometry_path/
weight: 70
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Memperbarui geometri bentuk dari objek [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath). Koordinat harus relatif terhadap kiri
             sudut kiri atas bentuk.
             Mengubah tipe bentuk ([`IGeometryShape.shape_type`](/slides/python-net/id/aspose.slides/igeometryshape/shape_type)) menjadi [`ShapeType.CUSTOM`](/slides/python-net/id/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath) | Jalur geometri |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Jalur tidak ditemukan |
| **RuntimeError(Proxy error(ArgumentException))** | Jalur kosong ditemukan |

### Lihat Juga
* kelas [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath)
* kelas [`IGeometryShape`](/slides/python-net/id/aspose.slides/igeometryshape)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)