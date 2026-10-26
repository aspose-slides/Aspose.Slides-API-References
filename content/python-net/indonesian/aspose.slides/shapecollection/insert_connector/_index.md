---
title: insert_connector method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/shapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Membuat bentuk penghubung baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, menerapkan gaya templat default.

### Mengembalikan

[`IConnector`](/slides/python-net/id/aspose.slides/iconnector) yang baru dibuat.



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol tempat menyisipkan bentuk penghubung. |
| shape_type | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) bentuk penghubung yang akan disisipkan. |
| x | **float** | Koordinat x dari bingkai penghubung, dalam poin. |
| y | **float** | Koordinat y dari bingkai penghubung, dalam poin. |
| width | **float** | Lebar bingkai penghubung, dalam poin. |
| height | **float** | Tinggi bingkai penghubung, dalam poin. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Membuat bentuk penghubung baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, dengan pilihan menerapkan gaya templat default.

### Mengembalikan

[`IConnector`](/slides/python-net/id/aspose.slides/iconnector) yang baru dibuat.



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol tempat menyisipkan bentuk penghubung. |
| shape_type | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) bentuk penghubung yang akan disisipkan. |
| x | **float** | Koordinat x dari bingkai penghubung, dalam poin. |
| y | **float** | Koordinat y dari bingkai penghubung, dalam poin. |
| width | **float** | Lebar bingkai penghubung, dalam poin. |
| height | **float** | Tinggi bingkai penghubung, dalam poin. |
| create_from_template | **bool** | True untuk menerapkan gaya templat default (nama tidak kosong, gaya sederhana);<br/><br/>false untuk membuat penghubung dengan nilai properti default. |



### Lihat Juga
* kelas [`IConnector`](/slides/python-net/id/aspose.slides/iconnector)
* kelas [`ShapeCollection`](/slides/python-net/id/aspose.slides/shapecollection)
* enumerasi [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)