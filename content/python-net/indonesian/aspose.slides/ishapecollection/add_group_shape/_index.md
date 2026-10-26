---
title: add_group_shape method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ishapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Membuat grup shape baru yang kosong dan menambahkannya ke akhir koleksi shape.
            Frame grup akan otomatis menyesuaikan untuk menampung semua shape yang ditambahkan ke dalamnya.

### Mengembalikan

[`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape) yang baru dibuat.



```python
def add_group_shape(self):
    ...
```



## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Membuat grup shape baru, mengonversi gambar SVG yang ditentukan menjadi shape individu, dan menambahkan grup hasil konversi ke akhir koleksi shape.

### Mengembalikan

[`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape) yang baru dibuat.



```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/id/aspose.slides/isvgimage) | [`ISvgImage`](/slides/python-net/id/aspose.slides/isvgimage) yang berisi konten vektor untuk dikonversi menjadi shape. |
| x | **float** | Koordinat x dari frame grup, dalam poin. |
| y | **float** | Koordinat y dari frame grup, dalam poin. |
| width | **float** | Lebar frame grup, dalam poin. |
| height | **float** | Tinggi frame grup, dalam poin. |



### Lihat Juga
* kelas [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape)
* kelas [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection)
* kelas [`ISvgImage`](/slides/python-net/id/aspose.slides/isvgimage)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)