---
title: add_zoom_frame method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ishapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Membuat Zoom frame baru dan menambahkannya ke akhir koleksi shape.

### Mengembalikan

[`IZoomFrame`](/slides/python-net/id/aspose.slides/izoomframe) yang baru dibuat.



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **float** | Koordinat x dari Zoom frame baru, dalam poin. |
| y | **float** | Koordinat y dari Zoom frame baru, dalam poin. |
| width | **float** | Lebar Zoom frame baru, dalam poin. |
| height | **float** | Tinggi Zoom frame baru, dalam poin. |
| slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | [`ISlide`](/slides/python-net/id/aspose.slides/islide) yang direferensikan oleh Zoom frame;<br/><br/>            harus menjadi milik presentasi ini. |

### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilempar jika slide yang direferensikan tidak menjadi milik presentasi saat ini. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Membuat Zoom frame baru dan menambahkannya ke akhir koleksi shape.

### Mengembalikan

[`IZoomFrame`](/slides/python-net/id/aspose.slides/izoomframe) yang baru dibuat.



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **float** | Koordinat x dari Zoom frame baru, dalam poin. |
| y | **float** | Koordinat y dari Zoom frame baru, dalam poin. |
| width | **float** | Lebar Zoom frame baru, dalam poin. |
| height | **float** | Tinggi Zoom frame baru, dalam poin. |
| slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | [`ISlide`](/slides/python-net/id/aspose.slides/islide) yang direferensikan oleh Zoom frame;<br/><br/>            harus menjadi milik presentasi ini. |
| image | [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage) | Gambar untuk slide yang direferensikan [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage). |

### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilempar jika slide yang direferensikan tidak menjadi milik presentasi saat ini. |



### Lihat Juga
* kelas [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage)
* kelas [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection)
* kelas [`ISlide`](/slides/python-net/id/aspose.slides/islide)
* kelas [`IZoomFrame`](/slides/python-net/id/aspose.slides/izoomframe)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)