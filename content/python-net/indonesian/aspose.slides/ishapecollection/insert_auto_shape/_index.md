---
title: insert_auto_shape method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Membuat auto shape baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan, menerapkan pemformatan templat default.

### Mengembalikan

[`IAutoShape`](/slides/python-net/id/aspose.slides/iautoshape) yang baru dibuat.



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol tempat menyisipkan auto shape baru. |
| shape_type | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) auto shape yang akan disisipkan. |
| x | **float** | Koordinat x dari bingkai shape, dalam poin. |
| y | **float** | Koordinat y dari bingkai shape, dalam poin. |
| width | **float** | Lebar bingkai shape, dalam poin. |
| height | **float** | Tinggi bingkai shape, dalam poin. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Membuat auto shape baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan, secara opsional menginisialisasinya dengan gaya templat default.

### Mengembalikan

[`IAutoShape`](/slides/python-net/id/aspose.slides/iautoshape) yang baru dibuat.



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol tempat menyisipkan auto shape. |
| shape_type | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) auto shape yang akan disisipkan. |
| x | **float** | Koordinat x dari bingkai shape, dalam poin. |
| y | **float** | Koordinat y dari bingkai shape, dalam poin. |
| width | **float** | Lebar bingkai shape, dalam poin. |
| height | **float** | Tinggi bingkai shape, dalam poin. |
| create_from_template | **bool** | True untuk menerapkan gaya templat default (termasuk nama yang tidak kosong, gaya sederhana, dan teks terpusat); <br/><br/> false untuk membuat shape dengan semua properti diatur ke nilai defaultnya. |



### Lihat Juga
* kelas [`IAutoShape`](/slides/python-net/id/aspose.slides/iautoshape)
* kelas [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection)
* enumerasi [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)