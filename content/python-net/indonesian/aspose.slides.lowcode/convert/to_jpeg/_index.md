---
title: to_jpeg method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
Mengonversi presentasi masukan menjadi sekumpulan gambar berformat JPEG.  
Jika nama berkas output diberikan sebagai "myPath/myFilename.jpeg", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.jpeg", di mana N adalah nomor slide.


```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/id/aspose.slides/presentation) | Presentasi masukan. |
| output_file_name | **str** | Nama berkas output. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
Mengonversi presentasi masukan menjadi sekumpulan gambar berformat JPEG.  
Jika nama berkas output diberikan sebagai "myPath/myFilename.jpeg", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.jpeg", di mana N adalah nomor slide.


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/id/aspose.slides/presentation) | Presentasi masukan |
| output_file_name | **str** | Nama berkas output. |
| image_size | **aspose.slides.Size** | Ukuran masing-masing gambar yang dihasilkan. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Mengonversi presentasi masukan menjadi sekumpulan gambar berformat JPEG.  
Jika nama berkas output diberikan sebagai "myPath/myFilename.jpeg", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.jpeg", di mana N adalah nomor slide.


```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/id/aspose.slides/presentation) | Presentasi masukan. |
| output_file_name | **str** | Nama berkas output. |
| scale | **float** | Faktor skala yang diterapkan pada gambar output relatif terhadap ukuran slide asli. |
| options | [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions) | Opsi rendering. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Lihat Juga
* kelas [`Convert`](/slides/python-net/id/aspose.slides.lowcode/convert)
* kelas [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions)
* kelas [`Presentation`](/slides/python-net/id/aspose.slides/presentation)
* modul [`aspose.slides.lowcode`](/slides/python-net/id/aspose.slides.lowcode)
* pustaka [`Aspose.Slides`](/slides/python-net)