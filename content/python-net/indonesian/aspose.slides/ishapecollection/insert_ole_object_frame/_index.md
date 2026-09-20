---
title: insert_ole_object_frame method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Membuat bingkai objek OLE baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

### Mengembalikan

[`IOleObjectFrame`](/slides/python-net/id/aspose.slides/ioleobjectframe) yang baru dibuat.



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol di mana bingkai objek OLE akan disisipkan. |
| x | **float** | Koordinat x dari bingkai OLE baru, dalam poin. |
| y | **float** | Koordinat y dari bingkai OLE baru, dalam poin. |
| width | **float** | Lebar bingkai OLE baru, dalam poin. |
| height | **float** | Tinggi bingkai OLE baru, dalam poin. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/id/aspose.slides/ioleembeddeddatainfo) | Informasi data OLE yang tersemat ([`IOleEmbeddedDataInfo`](/slides/python-net/id/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Membuat bingkai objek OLE baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

### Mengembalikan

[`IOleObjectFrame`](/slides/python-net/id/aspose.slides/ioleobjectframe) yang baru dibuat.



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol di mana bingkai objek OLE akan disisipkan. |
| x | **float** | Koordinat x dari bingkai OLE baru, dalam poin. |
| y | **float** | Koordinat y dari bingkai OLE baru, dalam poin. |
| width | **float** | Lebar bingkai OLE baru, dalam poin. |
| height | **float** | Tinggi bingkai OLE baru, dalam poin. |
| class_name | **str** | Nama kelas dari objek OLE. |
| path | **str** | Jalur ke file yang ditautkan. <br/><br/>Jalur ini disimpan persis dalam presentasi.<br/><br/>Jika jalur relatif ditentukan, file tidak akan dapat diakses saat membuka presentasi dari direktori yang berbeda. |



### Lihat Juga
* kelas [`IOleEmbeddedDataInfo`](/slides/python-net/id/aspose.slides/ioleembeddeddatainfo)
* kelas [`IOleObjectFrame`](/slides/python-net/id/aspose.slides/ioleobjectframe)
* kelas [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)