---
title: get_image method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Mengembalikan objek Thumbnail Image (20% dari ukuran sebenarnya).


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
Mengembalikan objek Thumbnail Image dengan ukuran yang ditentukan.

### Mengembalikan

Image object.



```python
def get_image(self, image_size):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/id/aspose.slides/size) | Ukuran gambar yang akan dibuat. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Mengembalikan objek Thumbnail tiff image dengan parameter yang ditentukan.

### Mengembalikan

Image object.



```python
def get_image(self, options):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/id/aspose.slides.export/itiffoptions) | Opsi tiff. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Dilempar ketika options.SlideLayoutOption adalah NotesCommentsLayoutingOptions dan propertinya NotesPosition mengambil nilai NotesPositions.BottomFull. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Mengembalikan objek Thumbnail Image.

### Mengembalikan

Image object.



```python
def get_image(self, options):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions) | Opsi rendering. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Dilempar ketika notesCommentsLayouting.NotesPosition mengambil nilai NotesPositions.BottomFull. |


## get_image(self, scale_x, scale_y) {#float-float}
Mengembalikan objek Thumbnail Image dengan skala khusus.

### Mengembalikan

IImage object.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| scale_x | **float** | Nilai yang digunakan untuk memperbesar Thumbnail ini pada arah sumbu x. |
| scale_y | **float** | Nilai yang digunakan untuk memperbesar Thumbnail ini pada arah sumbu y. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Mengembalikan objek Thumbnail Image dengan ukuran yang ditentukan.

### Mengembalikan

Image object.



```python
def get_image(self, options, image_size):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions) | Opsi rendering. |
| image_size | [`Size`](/slides/python-net/id/aspose.slides/size) | Ukuran gambar yang akan dibuat. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Dilempar ketika options.SlideLayoutOption adalah NotesCommentsLayoutingOptions dan propertinya NotesPosition mengambil nilai NotesPositions.BottomFull. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Mengembalikan objek Thumbnail Image dengan skala khusus.

### Mengembalikan

Bitmap objects.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions) | Opsi rendering. |
| scale_x | **float** | Nilai yang digunakan untuk memperbesar Thumbnail ini pada arah sumbu x. |
| scale_y | **float** | Nilai yang digunakan untuk memperbesar Thumbnail ini pada arah sumbu y. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Dilempar ketika notesCommentsLayouting.NotesPosition mengambil nilai NotesPositions.BottomFull. |



### Lihat Juga
* kelas [`IImage`](/slides/python-net/id/aspose.slides/iimage)
* kelas [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions)
* kelas [`ITiffOptions`](/slides/python-net/id/aspose.slides.export/itiffoptions)
* kelas [`Slide`](/slides/python-net/id/aspose.slides/slide)
* kelas [`Size`](/slides/python-net/id/aspose.slides/size)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)