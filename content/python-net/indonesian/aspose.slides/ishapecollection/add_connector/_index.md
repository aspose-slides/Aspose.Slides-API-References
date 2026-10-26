---
title: add_connector method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Membuat shape connector baru dengan gaya templat default dan menambahkannya ke akhir koleksi shape.

### Mengembalikan

[`IConnector`](/slides/python-net/id/aspose.slides/iconnector) yang baru dibuat.



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) dari shape connector yang akan ditambahkan. |
| x | **float** | Koordinat x dari frame connector, dalam poin. |
| y | **float** | Koordinat y dari frame connector, dalam poin. |
| width | **float** | Lebar frame connector, dalam poin. |
| height | **float** | Tinggi frame connector, dalam poin. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Membuat shape connector baru dan menambahkannya ke akhir koleksi shape, secara opsional menerapkan gaya templat default.

### Mengembalikan

[`IConnector`](/slides/python-net/id/aspose.slides/iconnector) yang baru dibuat.



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) dari shape connector yang akan dibuat. |
| x | **float** | Koordinat x dari frame connector, dalam poin. |
| y | **float** | Koordinat y dari frame connector, dalam poin. |
| width | **float** | Lebar frame connector, dalam poin. |
| height | **float** | Tinggi frame connector, dalam poin. |
| create_from_template | **bool** | True untuk menerapkan gaya templat default (nama tidak kosong, gaya sederhana); <br/><br/>            false untuk membuat connector dengan nilai properti default. |



### Lihat Juga
* kelas [`IConnector`](/slides/python-net/id/aspose.slides/iconnector)
* kelas [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection)
* enumerasi [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)