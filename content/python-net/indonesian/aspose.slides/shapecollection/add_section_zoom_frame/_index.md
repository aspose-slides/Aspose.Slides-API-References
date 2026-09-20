---
title: add_section_zoom_frame method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/shapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Membuat bingkai Section Zoom baru dan menambahkannya ke akhir koleksi shape.

### Mengembalikan

[`ISectionZoomFrame`](/slides/python-net/id/aspose.slides/isectionzoomframe) yang baru dibuat.



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **float** | Koordinat x dari bingkai Section Zoom baru, dalam poin. |
| y | **float** | Koordinat y dari bingkai Section Zoom baru, dalam poin. |
| width | **float** | Lebar bingkai Section Zoom baru, dalam poin. |
| height | **float** | Tinggi bingkai Section Zoom baru, dalam poin. |
| section | [`ISection`](/slides/python-net/id/aspose.slides/isection) | [`ISection`](/slides/python-net/id/aspose.slides/isection) yang direferensikan oleh bingkai Section Zoom; <br/><br/>            harus menjadi milik presentasi ini dan berisi setidaknya satu slide. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan jika bagian yang direferensikan tidak menjadi milik presentasi saat ini atau tidak berisi slide. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Membuat bingkai Section Zoom baru dengan gambar yang telah ditentukan dan menambahkannya ke akhir koleksi shape.

### Mengembalikan

[`ISectionZoomFrame`](/slides/python-net/id/aspose.slides/isectionzoomframe) yang baru dibuat.



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **float** | Koordinat x dari bingkai Section Zoom baru, dalam poin. |
| y | **float** | Koordinat y dari bingkai Section Zoom baru, dalam poin. |
| width | **float** | Lebar bingkai Section Zoom baru, dalam poin. |
| height | **float** | Tinggi bingkai Section Zoom baru, dalam poin. |
| section | [`ISection`](/slides/python-net/id/aspose.slides/isection) | [`ISection`](/slides/python-net/id/aspose.slides/isection) yang direferensikan oleh bingkai Section Zoom; <br/><br/>            harus menjadi milik presentasi ini dan berisi setidaknya satu slide. |
| image | [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage) yang akan ditampilkan dalam bingkai Section Zoom. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan jika bagian yang direferensikan tidak menjadi milik presentasi saat ini atau tidak berisi slide. |



### Lihat Juga
* kelas [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage)
* kelas [`ISection`](/slides/python-net/id/aspose.slides/isection)
* kelas [`ISectionZoomFrame`](/slides/python-net/id/aspose.slides/isectionzoomframe)
* kelas [`ShapeCollection`](/slides/python-net/id/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)