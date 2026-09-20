---
title: to_png method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
Mengonversi presentasi input menjadi serangkaian gambar format PNG.  
Jika nama berkas output diberikan sebagai "myPath/myFilename.png", 
hasilnya akan disimpan sebagai serangkaian berkas "myPath/myFilename_N.png", di mana N adalah nomor slide.


```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/id/aspose.slides/presentation) | Presentasi input. |
| output_file_name | **str** | Nama berkas output. |

### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
Mengonversi presentasi input menjadi serangkaian gambar format PNG.  
Jika nama berkas output diberikan sebagai "myPath/myFilename.png", 
hasilnya akan disimpan sebagai serangkaian berkas "myPath/myFilename_N.png", di mana N adalah nomor slide.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/id/aspose.slides/presentation) | Presentasi input |
| output_file_name | **str** | Nama berkas output. |
| image_size | **aspose.slides.Size** | Ukuran setiap gambar yang dihasilkan. |

### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Mengonversi presentasi input menjadi serangkaian gambar format PNG.  
Jika nama berkas output diberikan sebagai "myPath/myFilename.png", 
hasilnya akan disimpan sebagai serangkaian berkas "myPath/myFilename_N.png", di mana N adalah nomor slide.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/id/aspose.slides/presentation) | Presentasi input. |
| output_file_name | **str** | Nama berkas output. |
| scale | **float** | Faktor skala yang diterapkan pada gambar output relatif terhadap ukuran slide asli. |
| options | [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions) | Opsi rendering. |

### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Lihat Juga
* kelas [`Convert`](/slides/python-net/id/aspose.slides.lowcode/convert)
* kelas [`IRenderingOptions`](/slides/python-net/id/aspose.slides.export/irenderingoptions)
* kelas [`Presentation`](/slides/python-net/id/aspose.slides/presentation)
* modul [`aspose.slides.lowcode`](/slides/python-net/id/aspose.slides.lowcode)
* perpustakaan [`Aspose.Slides`](/slides/python-net)