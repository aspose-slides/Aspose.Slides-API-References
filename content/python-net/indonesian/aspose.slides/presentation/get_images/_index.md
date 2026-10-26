---
title: get_images method
second_title: Referensi API Aspose.Slides untuk Python melalui .NET
description: 
type: docs
url: /id/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Mengembalikan objek Image untuk semua slide pada presentasi.

### Mengembalikan

objek Image.

```python
def get_images(self, options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions) | Opsi Tiff. |

## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Mengembalikan objek Thumbnail Image untuk slide tertentu pada presentasi.

### Mengembalikan

objek Image.

```python
def get_images(self, options, slides):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions) | Opsi Tiff. |
| slides | **List[int]** | Array dengan posisi slide, dimulai dari 1. |

## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Mengembalikan objek Thumbnail Image untuk semua slide pada presentasi dengan ukuran tertentu.

### Mengembalikan

objek Image.

```python
def get_images(self, options, image_size):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions) | Opsi Tiff. |
| image_size | [`Size`](/slides/python-net/id/aspose.slides/size) | Ukuran gambar yang akan dibuat. |

## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Mengembalikan objek Thumbnail Image untuk semua slide pada presentasi dengan skala khusus.

### Mengembalikan

objek Image.

```python
def get_images(self, options, scale_x, scale_y):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions) | Opsi Tiff. |
| scale_x | **float** | Nilai yang digunakan untuk memperbesar Thumbnail ini pada arah sumbu x. |
| scale_y | **float** | Nilai yang digunakan untuk memperbesar Thumbnail ini pada arah sumbu y. |

## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Mengembalikan objek Thumbnail Image untuk slide tertentu pada presentasi dengan ukuran tertentu.

### Mengembalikan

objek Image.

```python
def get_images(self, options, slides, image_size):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions) | Opsi Tiff. |
| slides | **List[int]** | Array dengan posisi slide, dimulai dari 1. |
| image_size | [`Size`](/slides/python-net/id/aspose.slides/size) | Ukuran gambar yang akan dibuat. |

## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Mengembalikan objek Thumbnail Image untuk slide tertentu pada presentasi dengan skala khusus.

### Mengembalikan

objek Image.

```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions) | Opsi Tiff. |
| slides | **List[int]** | Array dengan posisi slide, dimulai dari 1. |
| scale_x | **float** | Nilai yang digunakan untuk memperbesar Thumbnail ini pada arah sumbu x. |
| scale_y | **float** | Nilai yang digunakan untuk memperbesar Thumbnail ini pada arah sumbu y. |

### Lihat Juga
* kelas [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions)
* kelas [`Presentation`](/slides/python-net/id/aspose.slides/presentation)
* kelas [`Size`](/slides/python-net/id/aspose.slides/size)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)