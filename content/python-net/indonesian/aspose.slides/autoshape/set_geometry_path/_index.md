---
title: set_geometry_path method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/autoshape/set_geometry_path/
weight: 90
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Memperbarui geometri bentuk dari objek [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath). Koordinat harus relatif terhadap sudut kiri atas bentuk. Mengubah jenis bentuk ([`GeometryShape.shape_type`](/slides/python-net/id/aspose.slides/geometryshape/shape_type)) menjadi [`ShapeType.CUSTOM`](/slides/python-net/id/aspose.slides/shapetype/CUSTOM).

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
* kelas [`AutoShape`](/slides/python-net/id/aspose.slides/autoshape)
* kelas [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)