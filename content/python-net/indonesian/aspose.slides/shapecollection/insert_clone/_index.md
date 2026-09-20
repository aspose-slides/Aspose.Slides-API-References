---
title: insert_clone method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/shapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.
            Bentuk yang dikloning mempertahankan posisi dan ukuran asli.

### Mengembalikan

[`IShape`](/slides/python-net/id/aspose.slides/ishape) yang baru dibuat.



```python
def insert_clone(self, index, source_shape):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol tempat menyisipkan bentuk yang dikloning. |
| source_shape | [`IShape`](/slides/python-net/id/aspose.slides/ishape) | [`IShape`](/slides/python-net/id/aspose.slides/ishape) yang akan dikloning. |


## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.
            Bentuk baru mempertahankan lebar dan tinggi `source_shape`.

### Mengembalikan

[`IShape`](/slides/python-net/id/aspose.slides/ishape) yang baru dibuat.



```python
def insert_clone(self, index, source_shape, x, y):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol tempat menyisipkan bentuk yang dikloning. |
| source_shape | [`IShape`](/slides/python-net/id/aspose.slides/ishape) | [`IShape`](/slides/python-net/id/aspose.slides/ishape) yang akan dikloning. |
| x | **float** | Koordinat x bingkai bentuk yang dikloning, dalam poin. |
| y | **float** | Koordinat y bingkai bentuk yang dikloning, dalam poin. |


## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

### Mengembalikan

[`IShape`](/slides/python-net/id/aspose.slides/ishape) yang baru dibuat.



```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol tempat menyisipkan bentuk yang dikloning. |
| source_shape | [`IShape`](/slides/python-net/id/aspose.slides/ishape) | [`IShape`](/slides/python-net/id/aspose.slides/ishape) yang akan dikloning. |
| x | **float** | Koordinat x bingkai bentuk yang dikloning, dalam poin. |
| y | **float** | Koordinat y bingkai bentuk yang dikloning, dalam poin. |
| width | **float** | Lebar bingkai bentuk yang dikloning, dalam poin. |
| height | **float** | Tinggi bingkai bentuk yang dikloning, dalam poin. |



### Lihat Juga
* kelas [`IShape`](/slides/python-net/id/aspose.slides/ishape)
* kelas [`ShapeCollection`](/slides/python-net/id/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)