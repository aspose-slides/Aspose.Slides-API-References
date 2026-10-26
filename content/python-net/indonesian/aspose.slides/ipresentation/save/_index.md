---
title: save method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ipresentation/save/
weight: 80
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Menyimpan semua slide presentasi ke sekumpulan file yang mewakili markup XAML.


```python
def save(self, options):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/id/aspose.slides.export.xaml/ixamloptions) | Opsi format XAML. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Menyimpan semua slide presentasi ke sebuah file dengan format yang ditentukan.


```python
def save(self, fname, format):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| fname | **str** | Jalur ke file yang dibuat. |
| format | [`SaveFormat`](/slides/python-net/id/aspose.slides.export/saveformat) | Format data yang diekspor. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Menyimpan semua slide presentasi ke aliran (stream) dalam format yang ditentukan.


```python
def save(self, stream, format):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | **io.RawIOBase** | Aliran keluaran. |
| format | [`SaveFormat`](/slides/python-net/id/aspose.slides.export/saveformat) | Format data yang diekspor. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Menyimpan semua slide presentasi ke sebuah file dengan format yang ditentukan dan dengan opsi tambahan.


```python
def save(self, fname, format, options):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| fname | **str** | Jalur ke file yang dibuat. |
| format | [`SaveFormat`](/slides/python-net/id/aspose.slides.export/saveformat) | Format data yang diekspor. |
| options | [`ISaveOptions`](/slides/python-net/id/aspose.slides.export/isaveoptions) | Opsi format tambahan. |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Menyimpan semua slide presentasi ke aliran (stream) dalam format yang ditentukan dan dengan opsi tambahan.


```python
def save(self, stream, format, options):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | **io.RawIOBase** | Aliran keluaran. |
| format | [`SaveFormat`](/slides/python-net/id/aspose.slides.export/saveformat) | Format data yang diekspor. |
| options | [`ISaveOptions`](/slides/python-net/id/aspose.slides.export/isaveoptions) | Opsi format tambahan. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Jika Anda mencoba menyimpan file terenkripsi dalam <br/> format Office 2007-2010 yang tidak didukung |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Menyimpan slide tertentu dari presentasi ke sebuah file dengan format yang ditentukan.


```python
def save(self, fname, slides, format):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| fname | **str** | Jalur ke file yang dibuat. |
| slides | **List[int]** | Array dengan posisi slide, dimulai dari 1. |
| format | [`SaveFormat`](/slides/python-net/id/aspose.slides.export/saveformat) | Format data yang diekspor. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ketika parameter stream atau slides bernilai None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ketika parameter slides berisi nomor halaman yang salah. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ketika SaveFormat yang tidak didukung digunakan, misalnya PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Menyimpan slide tertentu dari presentasi ke aliran (stream) dalam format yang ditentukan.


```python
def save(self, stream, slides, format):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | **io.RawIOBase** | Aliran keluaran. |
| slides | **List[int]** | Array dengan posisi slide, dimulai dari 1. |
| format | [`SaveFormat`](/slides/python-net/id/aspose.slides.export/saveformat) | Format data yang diekspor. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ketika parameter stream atau slides bernilai None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ketika parameter slides berisi nomor halaman yang salah. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ketika SaveFormat yang tidak didukung digunakan, misalnya PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Menyimpan slide tertentu dari presentasi ke sebuah file dengan format yang ditentukan.


```python
def save(self, fname, slides, format, options):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| fname | **str** | Jalur ke file yang dibuat. |
| slides | **List[int]** | Array dengan posisi slide, dimulai dari 1. |
| format | [`SaveFormat`](/slides/python-net/id/aspose.slides.export/saveformat) | Format data yang diekspor. |
| options | [`ISaveOptions`](/slides/python-net/id/aspose.slides.export/isaveoptions) | Opsi format tambahan. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ketika parameter stream atau slides bernilai None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ketika parameter slides berisi nomor halaman yang salah. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ketika SaveFormat yang tidak didukung digunakan, misalnya PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Menyimpan slide tertentu dari presentasi ke aliran (stream) dalam format yang ditentukan.


```python
def save(self, stream, slides, format, options):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | **io.RawIOBase** | Aliran keluaran. |
| slides | **List[int]** | Array dengan posisi slide, dimulai dari 1. |
| format | [`SaveFormat`](/slides/python-net/id/aspose.slides.export/saveformat) | Format data yang diekspor. |
| options | [`ISaveOptions`](/slides/python-net/id/aspose.slides.export/isaveoptions) | Opsi format tambahan. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ketika parameter stream atau slides bernilai None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ketika parameter slides berisi nomor halaman yang salah. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ketika SaveFormat yang tidak didukung digunakan, misalnya PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Lihat Juga
* kelas [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation)
* kelas [`ISaveOptions`](/slides/python-net/id/aspose.slides.export/isaveoptions)
* kelas [`IXamlOptions`](/slides/python-net/id/aspose.slides.export.xaml/ixamloptions)
* enumerasi [`SaveFormat`](/slides/python-net/id/aspose.slides.export/saveformat)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)