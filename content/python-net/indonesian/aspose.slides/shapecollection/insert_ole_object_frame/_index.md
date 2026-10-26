---
title: insert_ole_object_frame method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/shapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Membuat frame objek OLE baru dan memasukkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

### Mengembalikan

Objek [`IOleObjectFrame`](/slides/python-net/id/aspose.slides/ioleobjectframe) yang baru dibuat.

```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol tempat frame objek OLE akan disisipkan. |
| x | **float** | Koordinat x dari frame OLE baru, dalam poin. |
| y | **float** | Koordinat y dari frame OLE baru, dalam poin. |
| width | **float** | Lebar frame OLE baru, dalam poin. |
| height | **float** | Tinggi frame OLE baru, dalam poin. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/id/aspose.slides/ioleembeddeddatainfo) | Informasi data OLE tertanam ([`IOleEmbeddedDataInfo`](/slides/python-net/id/aspose.slides/ioleembeddeddatainfo)). |

## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Membuat frame objek OLE baru dan memasukkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

### Mengembalikan

OLE object frame yang baru dibuat.

```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol tempat frame objek OLE akan disisipkan. |
| x | **float** | Koordinat x dari frame OLE baru, dalam poin. |
| y | **float** | Koordinat y dari frame OLE baru, dalam poin. |
| width | **float** | Lebar frame OLE baru, dalam poin. |
| height | **float** | Tinggi frame OLE baru, dalam poin. |
| class_name | **str** | Nama kelas objek OLE. |
| path | **str** | Path ke file yang ditautkan. <br/><br/>Path ini disimpan persis dalam presentasi.<br/><br/>Jika path relatif ditentukan, file tidak akan dapat diakses saat membuka<br/><br/>presentasi dari direktori yang berbeda. |

### Lihat Juga
* kelas [`IOleEmbeddedDataInfo`](/slides/python-net/id/aspose.slides/ioleembeddeddatainfo)
* kelas [`IOleObjectFrame`](/slides/python-net/id/aspose.slides/ioleobjectframe)
* kelas [`ShapeCollection`](/slides/python-net/id/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)