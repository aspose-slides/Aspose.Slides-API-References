---
title: insert_zoom_frame method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Membuat Zoom frame baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

### Mengembalikan

[`IZoomFrame`](/slides/python-net/id/aspose.slides/izoomframe) yang baru dibuat.

```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol tempat menyisipkan Zoom frame. |
| x | **float** | Koordinat x dari Zoom frame baru, dalam point. |
| y | **float** | Koordinat y dari Zoom frame baru, dalam point. |
| width | **float** | Lebar Zoom frame baru, dalam point. |
| height | **float** | Tinggi Zoom frame baru, dalam point. |
| slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | [`ISlide`](/slides/python-net/id/aspose.slides/islide) yang dirujuk oleh Zoom frame. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan jika slide yang dirujuk tidak termasuk dalam presentasi saat ini. |

## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Membuat Zoom frame baru dengan gambar yang telah ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

### Mengembalikan

[`IZoomFrame`](/slides/python-net/id/aspose.slides/izoomframe) yang baru dibuat.

```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol tempat menyisipkan Zoom frame. |
| x | **float** | Koordinat x dari Zoom frame baru, dalam point. |
| y | **float** | Koordinat y dari Zoom frame baru, dalam point. |
| width | **float** | Lebar Zoom frame baru, dalam point. |
| height | **float** | Tinggi Zoom frame baru, dalam point. |
| slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | [`ISlide`](/slides/python-net/id/aspose.slides/islide) yang dirujuk oleh Zoom frame. |
| image | [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage) | Gambar untuk slide [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage) yang dirujuk. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan jika slide yang dirujuk tidak termasuk dalam presentasi saat ini. |

### Lihat Juga
* kelas [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage)
* kelas [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection)
* kelas [`ISlide`](/slides/python-net/id/aspose.slides/islide)
* kelas [`IZoomFrame`](/slides/python-net/id/aspose.slides/izoomframe)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)