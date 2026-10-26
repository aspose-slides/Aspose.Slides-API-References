---
title: insert_section_zoom_frame method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Membuat frame Section Zoom baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan.

### Returns
[`ISectionZoomFrame`](/slides/python-net/id/aspose.slides/isectionzoomframe) yang baru dibuat.



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol tempat menyisipkan frame Section Zoom. |
| x | **float** | Koordinat x dari frame Section Zoom baru, dalam point. |
| y | **float** | Koordinat y dari frame Section Zoom baru, dalam point. |
| width | **float** | Lebar frame Section Zoom baru, dalam point. |
| height | **float** | Tinggi frame Section Zoom baru, dalam point. |
| section | [`ISection`](/slides/python-net/id/aspose.slides/isection) | [`ISection`](/slides/python-net/id/aspose.slides/isection) yang direferensikan oleh frame Section Zoom;<br/><br/>            harus menjadi bagian dari presentasi ini dan berisi setidaknya satu slide. |

### Exceptions

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilempar jika bagian yang direferensikan tidak termasuk dalam presentasi saat ini atau tidak berisi slide. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Membuat frame Section Zoom baru dengan gambar yang telah ditentukan dan menyisipkannya ke koleksi shape pada indeks yang ditentukan.

### Returns
[`ISectionZoomFrame`](/slides/python-net/id/aspose.slides/isectionzoomframe) yang baru dibuat.



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol tempat menyisipkan frame Section Zoom. |
| x | **float** | Koordinat x dari frame Section Zoom baru, dalam point. |
| y | **float** | Koordinat y dari frame Section Zoom baru, dalam point. |
| width | **float** | Lebar frame Section Zoom baru, dalam point. |
| height | **float** | Tinggi frame Section Zoom baru, dalam point. |
| section | [`ISection`](/slides/python-net/id/aspose.slides/isection) | [`ISection`](/slides/python-net/id/aspose.slides/isection) yang direferensikan oleh frame Section Zoom;<br/><br/>            harus menjadi bagian dari presentasi ini dan berisi setidaknya satu slide. |
| image | [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage) | Gambar yang akan ditampilkan di dalam frame Section Zoom. |

### Exceptions

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilempar jika bagian yang direferensikan tidak termasuk dalam presentasi saat ini atau tidak berisi slide. |



### Lihat Juga
* kelas [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage)
* kelas [`ISection`](/slides/python-net/id/aspose.slides/isection)
* kelas [`ISectionZoomFrame`](/slides/python-net/id/aspose.slides/isectionzoomframe)
* kelas [`ShapeCollection`](/slides/python-net/id/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)