---
title: add_ole_object_frame method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/ishapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi shape.

### Mengembalikan

[`IOleObjectFrame`](/slides/python-net/id/aspose.slides/ioleobjectframe) yang baru dibuat.



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **float** | Koordinat x dari bingkai OLE baru, dalam point. |
| y | **float** | Koordinat y dari bingkai OLE baru, dalam point. |
| width | **float** | Lebar bingkai OLE baru, dalam point. |
| height | **float** | Tinggi bingkai OLE baru, dalam point. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/id/aspose.slides/ioleembeddeddatainfo) | Informasi data OLE yang disematkan ([`IOleEmbeddedDataInfo`](/slides/python-net/id/aspose.slides/ioleembeddeddatainfo)). |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi shape.

### Mengembalikan

[`IOleObjectFrame`](/slides/python-net/id/aspose.slides/ioleobjectframe) yang baru dibuat.



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **float** | Koordinat x dari bingkai OLE baru, dalam point. |
| y | **float** | Koordinat y dari bingkai OLE baru, dalam point. |
| width | **float** | Lebar bingkai OLE baru, dalam point. |
| height | **float** | Tinggi bingkai OLE baru, dalam point. |
| class_name | **str** | Nama kelas dari objek OLE. |
| path | **str** | Jalur ke file yang ditautkan. <br/><br/>Jalur ini disimpan persis dalam presentasi.<br/><br/>            Jika jalur relatif ditentukan, file tidak akan dapat diakses saat membuka<br/><br/>            presentasi dari direktori yang berbeda. |



### Lihat Juga
* kelas [`IOleEmbeddedDataInfo`](/slides/python-net/id/aspose.slides/ioleembeddeddatainfo)
* kelas [`IOleObjectFrame`](/slides/python-net/id/aspose.slides/ioleobjectframe)
* kelas [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)