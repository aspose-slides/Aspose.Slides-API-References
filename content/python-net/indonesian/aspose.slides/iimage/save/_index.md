---
title: save method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
Menyimpan gambar ke file.


```python
def save(self, filename):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| filename | **str** | Jalur ke file tempat gambar akan disimpan. |


## save(self, filename, format) {#str-imageformat}
Menyimpan gambar ke file dalam format yang ditentukan.


```python
def save(self, filename, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| filename | **str** | Jalur ke file tempat gambar akan disimpan. |
| format | [`ImageFormat`](/slides/python-net/id/aspose.slides/imageformat) | Format gambar. |


## save(self, stream, format) {#iorawiobase-imageformat}
Menyimpan gambar ke aliran dalam format yang ditentukan.


```python
def save(self, stream, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Aliran tempat gambar akan disimpan. |
| format | [`ImageFormat`](/slides/python-net/id/aspose.slides/imageformat) | Format gambar. |


## save(self, filename, format, quality) {#str-imageformat-int}
Menyimpan gambar ke file dalam format dan kualitas yang ditentukan.


```python
def save(self, filename, format, quality):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| filename | **str** | Jalur ke file tempat gambar akan disimpan. |
| format | [`ImageFormat`](/slides/python-net/id/aspose.slides/imageformat) | Format gambar. |
| quality | **int** | Kualitas gambar yang disimpan (0 hingga 100).  <br/><br/>            Parameter ini hanya memengaruhi penyimpanan dalam [`ImageFormat.JPEG`](/slides/python-net/id/aspose.slides/imageformat/JPEG); untuk semua format lain, diabaikan. |


## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
Menyimpan gambar ke aliran dalam format dan kualitas yang ditentukan.


```python
def save(self, stream, format, quality):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Aliran tempat gambar akan disimpan. |
| format | [`ImageFormat`](/slides/python-net/id/aspose.slides/imageformat) | Format gambar. |
| quality | **int** | Kualitas gambar yang disimpan (0 hingga 100).  <br/><br/>            Parameter ini hanya memengaruhi penyimpanan dalam [`ImageFormat.JPEG`](/slides/python-net/id/aspose.slides/imageformat/JPEG); untuk semua format lain, diabaikan. |



### Lihat Juga
* kelas [`IImage`](/slides/python-net/id/aspose.slides/iimage)
* enumerasi [`ImageFormat`](/slides/python-net/id/aspose.slides/imageformat)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)