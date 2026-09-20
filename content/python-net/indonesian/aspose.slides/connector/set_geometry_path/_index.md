---
title: set_geometry_path method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/connector/set_geometry_path/
weight: 90
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Memperbarui geometri bentuk dari objek [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath). Koordinat harus relatif terhadap sudut kiri atas bentuk.
Mengubah tipe bentuk ([`GeometryShape.shape_type`](/slides/python-net/id/aspose.slides/geometryshape/shape_type)) menjadi [`ShapeType.CUSTOM`](/slides/python-net/id/aspose.slides/shapetype/CUSTOM).

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
| **RuntimeError(Proxy error(ArgumentException))** | Tidak ditemukan jalur |
| **RuntimeError(Proxy error(ArgumentException))** | Jalur kosong ditemukan |

### Lihat Juga
* kelas [`Connector`](/slides/python-net/id/aspose.slides/connector)
* kelas [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)