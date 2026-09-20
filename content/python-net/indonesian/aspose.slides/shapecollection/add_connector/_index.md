---
title: add_connector method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/shapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Membuat bentuk konektor baru dengan gaya templat default dan menambahkannya ke akhir
            koleksi bentuk.

### Mengembalikan

[`IConnector`](/slides/python-net/id/aspose.slides/iconnector) yang baru dibuat.



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) dari bentuk konektor yang akan ditambahkan. |
| x | **float** | Koordinat x dari bingkai konektor, dalam poin. |
| y | **float** | Koordinat y dari bingkai konektor, dalam poin. |
| width | **float** | Lebar bingkai konektor, dalam poin. |
| height | **float** | Tinggi bingkai konektor, dalam poin. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Membuat bentuk konektor baru dan menambahkannya ke akhir koleksi bentuk,
            secara opsional menerapkan gaya templat default.

### Mengembalikan

[`IConnector`](/slides/python-net/id/aspose.slides/iconnector) yang baru dibuat.



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) dari bentuk konektor yang akan dibuat. |
| x | **float** | Koordinat x dari bingkai konektor, dalam poin. |
| y | **float** | Koordinat y dari bingkai konektor, dalam poin. |
| width | **float** | Lebar bingkai konektor, dalam poin. |
| height | **float** | Tinggi bingkai konektor, dalam poin. |
| create_from_template | **bool** | True untuk menerapkan gaya templat default (nama tidak kosong, gaya sederhana); <br/><br/>false untuk membuat konektor dengan nilai properti default. |



### Lihat Juga
* kelas [`IConnector`](/slides/python-net/id/aspose.slides/iconnector)
* kelas [`ShapeCollection`](/slides/python-net/id/aspose.slides/shapecollection)
* enumerasi [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)