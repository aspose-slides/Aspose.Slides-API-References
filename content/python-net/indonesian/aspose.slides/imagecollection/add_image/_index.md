---
title: add_image method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
Menambahkan salinan gambar dari presentasi lain.

### Mengembalikan

Gambar yang ditambahkan.



```python
def add_image(self, image_source):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage) | Gambar sumber. |


## add_image(self, image) {#iimage}
Menambahkan gambar ke presentasi.

### Mengembalikan

Gambar yang ditambahkan.



```python
def add_image(self, image):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/id/aspose.slides/iimage) | Gambar yang akan ditambahkan. |

### Catatan

Metode ini mengonversi berkas metafile WMF/EMF menjadi gambar PNG raster sebelum dimasukkan ke presentasi.


## add_image(self, stream) {#iorawiobase}
Menambahkan gambar ke presentasi dari aliran.

### Mengembalikan

Gambar yang ditambahkan.



```python
def add_image(self, stream):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | **io.RawIOBase** | Aliran untuk menambahkan gambar dari. |

### Catatan

Metode ini dapat menambahkan berkas metafile WMF/EMF ke presentasi tanpa mengonversinya menjadi gambar PNG raster.


## add_image(self, buffer) {#bytes}
Menambahkan gambar ke presentasi dari buffer yang ditentukan.

### Mengembalikan

Gambar yang ditambahkan.



```python
def add_image(self, buffer):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| buffer | **bytes** | Buffer. |


## add_image(self, svg_image) {#isvgimage}
Menambahkan gambar ke presentasi dari objek Svg.

### Mengembalikan

Gambar yang ditambahkan.



```python
def add_image(self, svg_image):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/id/aspose.slides/isvgimage) | Objek gambar Svg [`ISvgImage`](/slides/python-net/id/aspose.slides/isvgimage) |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ketika parameter svgImage bernilai None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Membuat dan menambahkan gambar ke presentasi dari aliran.

### Mengembalikan

Ditambahkan [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | **io.RawIOBase** | Aliran untuk menambahkan file gambar dari. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/id/aspose.slides/loadingstreambehavior) | Perilaku yang akan diterapkan pada aliran. |



### Lihat Juga
* kelas [`IImage`](/slides/python-net/id/aspose.slides/iimage)
* kelas [`ImageCollection`](/slides/python-net/id/aspose.slides/imagecollection)
* kelas [`IPPImage`](/slides/python-net/id/aspose.slides/ippimage)
* kelas [`ISvgImage`](/slides/python-net/id/aspose.slides/isvgimage)
* enumerasi [`LoadingStreamBehavior`](/slides/python-net/id/aspose.slides/loadingstreambehavior)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)