---
title: add_section_zoom_frame method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Membuat frame Section Zoom baru dan menambahkannya ke akhir koleksi shape.

### Mengembalikan

[`ISectionZoomFrame`](/slides/python-net/id/aspose.slides/isectionzoomframe) yang baru dibuat.



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **float** | Koordinat x dari frame Section Zoom baru, dalam poin. |
| y | **float** | Koordinat y dari frame Section Zoom baru, dalam poin. |
| width | **float** | Lebar frame Section Zoom baru, dalam poin. |
| height | **float** | Tinggi frame Section Zoom baru, dalam poin. |
| section | [`ISection`](/slides/python-net/id/aspose.slides/isection) | [`ISection`](/slides/python-net/id/aspose.slides/isection) yang direferensikan oleh frame Section Zoom; <br/><br/>            harus menjadi milik presentasi ini dan berisi setidaknya satu slide. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan jika bagian yang direferensikan tidak menjadi milik presentasi saat ini atau tidak berisi slide. |

## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Membuat frame Section Zoom baru dengan gambar yang telah ditentukan dan menambahkannya ke akhir koleksi shape.

### Mengembalikan

[`ISectionZoomFrame`](/slides/python-net/id/aspose.slides/isectionzoomframe) yang baru dibuat.



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **float** | Koordinat x dari frame Section Zoom baru, dalam poin. |
| y | **float** | Koordinat y dari frame Section Zoom baru, dalam poin. |
| width | **float** | Lebar frame Section Zoom baru, dalam poin. |
| height | **float** | Tinggi frame Section Zoom baru, dalam poin. |
| section | [`ISection`](/slides/python-net/id/aspose.slides/isection) | [`ISection`](/slides/python-net/id/aspose.slides/isection) yang direferensikan oleh frame Section Zoom; <br/><br/>            harus menjadi milik presentasi ini dan berisi setidaknya satu slide. |
| image | [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage) yang akan ditampilkan dalam frame Section Zoom. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan jika bagian yang direferensikan tidak menjadi milik presentasi saat ini atau tidak berisi slide. |


### Lihat Juga
* kelas [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage)
* kelas [`ISection`](/slides/python-net/id/aspose.slides/isection)
* kelas [`ISectionZoomFrame`](/slides/python-net/id/aspose.slides/isectionzoomframe)
* kelas [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)