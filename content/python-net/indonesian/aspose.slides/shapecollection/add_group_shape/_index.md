---
title: add_group_shape method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/shapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Membuat grup shape kosong baru dan menambahkannya ke akhir koleksi shape. Bingkai grup akan otomatis menyesuaikan diri untuk menampung semua shape yang ditambahkan.

### Mengembalikan
[`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape) yang baru dibuat.

```python
def add_group_shape(self):
    ...
```

## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Membuat grup shape baru, mengonversi gambar SVG yang ditentukan menjadi shape individual, dan menambahkan grup hasil konversi ke akhir koleksi shape. Bingkai grup akan otomatis menyesuaikan diri untuk menampung semua shape yang ditambahkan.

### Mengembalikan
[`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape) yang baru dibuat.

```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/id/aspose.slides/isvgimage) | [`ISvgImage`](/slides/python-net/id/aspose.slides/isvgimage) yang berisi konten vektor untuk dikonversi menjadi shape. |
| x | **float** | Koordinat x bingkai grup, dalam poin. |
| y | **float** | Koordinat y bingkai grup, dalam poin. |
| width | **float** | Lebar bingkai grup, dalam poin. |
| height | **float** | Tinggi bingkai grup, dalam poin. |

### Lihat Juga
* kelas [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape)
* kelas [`ISvgImage`](/slides/python-net/id/aspose.slides/isvgimage)
* kelas [`ShapeCollection`](/slides/python-net/id/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)