---
title: get_images method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Mengembalikan objek Thumbnail Image untuk semua slide dalam presentasi.

### Mengembalikan

objek Bitmap.



```python
def get_images(self, options):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions) | Opsi rendering. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Mengembalikan objek Thumbnail Bitmap untuk slide tertentu dalam presentasi.

### Mengembalikan

objek Bitmap.



```python
def get_images(self, options, slides):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions) | Opsi rendering. |
| slides | **List[int]** | Array dengan posisi slide, dimulai dari 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Mengembalikan objek Thumbnail Image untuk semua slide dalam presentasi dengan ukuran tertentu.

### Mengembalikan

objek Bitmap.



```python
def get_images(self, options, image_size):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions) | Opsi rendering. |
| image_size | [`Size`](/slides/python-net/id/aspose.slides/size) | Ukuran gambar yang akan dibuat. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Mengembalikan objek Thumbnail Image untuk semua slide dalam presentasi dengan skala khusus.

### Mengembalikan

objek Bitmap.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions) | Opsi rendering. |
| scale_x | **float** | Nilai untuk menskalakan Thumbnail ini pada arah sumbu x. |
| scale_y | **float** | Nilai untuk menskalakan Thumbnail ini pada arah sumbu y. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Mengembalikan objek Thumbnail Image untuk slide tertentu dalam presentasi dengan ukuran tertentu.

### Mengembalikan

objek Bitmap.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions) | Opsi rendering. |
| slides | **List[int]** | Array dengan posisi slide, dimulai dari 1. |
| image_size | [`Size`](/slides/python-net/id/aspose.slides/size) | Ukuran gambar yang akan dibuat. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Mengembalikan objek Thumbnail Image untuk slide tertentu dalam presentasi dengan skala khusus.

### Mengembalikan

objek Bitmap.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions) | Opsi rendering. |
| slides | **List[int]** | Array dengan posisi slide, dimulai dari 1. |
| scale_x | **float** | Nilai untuk menskalakan Thumbnail ini pada arah sumbu x. |
| scale_y | **float** | Nilai untuk menskalakan Thumbnail ini pada arah sumbu y. |



### Lihat Juga
* kelas [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation)
* kelas [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions)
* kelas [`Size`](/slides/python-net/id/aspose.slides/size)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)