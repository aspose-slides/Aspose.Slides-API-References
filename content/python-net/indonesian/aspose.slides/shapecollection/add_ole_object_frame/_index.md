---
title: add_ole_object_frame method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/shapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi shape.

### Mengembalikan

[`IOleObjectFrame`](/slides/python-net/id/aspose.slides/ioleobjectframe).

```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **float** | Koordinat x dari bingkai OLE baru, dalam poin. |
| y | **float** | Koordinat y dari bingkai OLE baru, dalam poin. |
| width | **float** | Lebar bingkai OLE baru, dalam poin. |
| height | **float** | Tinggi bingkai OLE baru, dalam poin. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/id/aspose.slides/ioleembeddeddatainfo) | Informasi tentang data OLE yang disematkan ([`IOleEmbeddedDataInfo`](/slides/python-net/id/aspose.slides/ioleembeddeddatainfo)). |

## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi shape.

### Mengembalikan

[`IOleObjectFrame`](/slides/python-net/id/aspose.slides/ioleobjectframe).

```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **float** | Koordinat x dari bingkai OLE baru, dalam poin. |
| y | **float** | Koordinat y dari bingkai OLE baru, dalam poin. |
| width | **float** | Lebar bingkai OLE baru, dalam poin. |
| height | **float** | Tinggi bingkai OLE baru, dalam poin. |
| class_name | **str** | Nama kelas dari objek OLE. |
| path | **str** | Jalur ke file yang ditautkan.<br/><br/>Jalur ini disimpan persis dalam presentasi.<br/><br/>Jika jalur relatif ditentukan, file tidak akan dapat diakses saat membuka presentasi dari direktori yang berbeda. |

### Lihat Juga
* class [`IOleEmbeddedDataInfo`](/slides/python-net/id/aspose.slides/ioleembeddeddatainfo)
* class [`IOleObjectFrame`](/slides/python-net/id/aspose.slides/ioleobjectframe)
* class [`ShapeCollection`](/slides/python-net/id/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)