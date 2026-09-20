---
title: add_auto_shape method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/shapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Membuat sebuah auto shape baru dengan format default dan menambahkannya ke akhir
            koleksi shape.

### Mengembalikan

[`IAutoShape`](/slides/python-net/id/aspose.slides/iautoshape) yang baru dibuat.



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) dari auto shape yang akan ditambahkan. |
| x | **float** | Koordinat x dari frame shape, dalam poin. |
| y | **float** | Koordinat y dari frame shape, dalam poin. |
| width | **float** | Lebar frame shape, dalam poin. |
| height | **float** | Tinggi frame shape, dalam poin. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Membuat sebuah auto shape baru dan menambahkannya ke akhir koleksi shape,
            secara opsional menginisialisasinya dengan format template default.

### Mengembalikan

[`IAutoShape`](/slides/python-net/id/aspose.slides/iautoshape) yang baru dibuat.



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype) dari auto shape yang akan ditambahkan. |
| x | **float** | Koordinat x dari frame shape, dalam poin. |
| y | **float** | Koordinat y dari frame shape, dalam poin. |
| width | **float** | Lebar frame shape, dalam poin. |
| height | **float** | Tinggi frame shape, dalam poin. |
| create_from_template | **bool** | True untuk menerapkan gaya template default (gaya sederhana, teks terpusat, dan nama yang tidak kosong)<br/><br/>            ke shape baru; false untuk membuat shape dengan semua properti diatur ke nilai default mereka. |



### Lihat Juga
* kelas [`IAutoShape`](/slides/python-net/id/aspose.slides/iautoshape)
* kelas [`ShapeCollection`](/slides/python-net/id/aspose.slides/shapecollection)
* enumerasi [`ShapeType`](/slides/python-net/id/aspose.slides/shapetype)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)