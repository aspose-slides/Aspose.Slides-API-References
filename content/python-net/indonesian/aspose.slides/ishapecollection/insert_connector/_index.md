---
title: insert_connector method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ishapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Membuat shape connector baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan,
            dengan menerapkan gaya templat default.

### Mengembalikan

Yang baru dibuat [`IConnector`](/slides/python-net/id/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol di mana shape connector akan disisipkan. |
| shape_type | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) dari shape connector yang akan disisipkan. |
| x | **float** | Koordinat x dari bingkai connector, dalam poin. |
| y | **float** | Koordinat y dari bingkai connector, dalam poin. |
| width | **float** | Lebar bingkai connector, dalam poin. |
| height | **float** | Tinggi bingkai connector, dalam poin. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Membuat shape connector baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan,
            secara opsional menerapkan gaya templat default.

### Mengembalikan

Yang baru dibuat [`IConnector`](/slides/python-net/id/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol di mana shape connector akan disisipkan. |
| shape_type | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) dari shape connector yang akan disisipkan. |
| x | **float** | Koordinat x dari bingkai connector, dalam poin. |
| y | **float** | Koordinat y dari bingkai connector, dalam poin. |
| width | **float** | Lebar bingkai connector, dalam poin. |
| height | **float** | Tinggi bingkai connector, dalam poin. |
| create_from_template | **bool** | True untuk menerapkan gaya templat default (nama tidak kosong, gaya sederhana);<br/><br/>false untuk membuat connector dengan nilai properti default. |



### Lihat Juga
* kelas [`IConnector`](/slides/python-net/id/aspose.slides/iconnector)
* kelas [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection)
* enumerasi [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)