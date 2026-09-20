---
title: set_geometry_paths method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/connector/set_geometry_paths/
weight: 100
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Memperbarui geometri bentuk dari array [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath). Koordinat harus relatif terhadap sudut kiri atas bentuk. Mengubah tipe bentuk ([`GeometryShape.shape_type`](/slides/python-net/id/aspose.slides/geometryshape/shape_type)) menjadi [`ShapeType.CUSTOM`](/slides/python-net/id/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Array jalur geometri |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Tidak ada jalur ditemukan |
| **RuntimeError(Proxy error(ArgumentException))** | Jalur kosong |

### Lihat Juga
* kelas [`Connector`](/slides/python-net/id/aspose.slides/connector)
* kelas [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)