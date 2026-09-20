---
title: set_geometry_paths method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/audioframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Memperbarui geometri bentuk dari array [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath). Koordinat harus relatif terhadap kiri
             sudut kiri atas bentuk.
             Mengubah tipe bentuk ([`GeometryShape.shape_type`](/slides/python-net/id/aspose.slides/geometryshape/shape_type)) menjadi [`ShapeType.CUSTOM`](/slides/python-net/id/aspose.slides/shapetype/CUSTOM).


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
| **RuntimeError(Proxy error(ArgumentException))** | Tidak ada jalur yang ditemukan |
| **RuntimeError(Proxy error(ArgumentException))** | Jalur kosong |



### Lihat Juga
* kelas [`AudioFrame`](/slides/python-net/id/aspose.slides/audioframe)
* kelas [`IGeometryPath`](/slides/python-net/id/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)