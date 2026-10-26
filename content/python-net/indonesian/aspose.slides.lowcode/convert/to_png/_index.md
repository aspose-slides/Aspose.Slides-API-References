---
title: to_png method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
Mengonversi presentasi masukan menjadi sekumpulan gambar berformat PNG.  
            Jika nama file output diberikan sebagai "myPath/myFilename.png", 
            hasilnya akan disimpan sebagai sekumpulan file "myPath/myFilename_N.png", di mana N adalah nomor slide.


```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/id/aspose.slides/presentation) | Presentasi masukan. |
| output_file_name | **str** | Nama file output. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
Mengonversi presentasi masukan menjadi sekumpulan gambar berformat PNG.  
            Jika nama file output diberikan sebagai "myPath/myFilename.png", 
            hasilnya akan disimpan sebagai sekumpulan file "myPath/myFilename_N.png", di mana N adalah nomor slide.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/id/aspose.slides/presentation) | Presentasi masukan |
| output_file_name | **str** | Nama file output. |
| image_size | [`Size`](/slides/python-net/id/aspose.slides/size) | Ukuran setiap gambar yang dihasilkan. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Mengonversi presentasi masukan menjadi sekumpulan gambar berformat PNG.  
            Jika nama file output diberikan sebagai "myPath/myFilename.png", 
            hasilnya akan disimpan sebagai sekumpulan file "myPath/myFilename_N.png", di mana N adalah nomor slide.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/id/aspose.slides/presentation) | Presentasi masukan. |
| output_file_name | **str** | Nama file output. |
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
* kelas [`Size`](/slides/python-net/id/aspose.slides/size)
* modul [`aspose.slides.lowcode`](/slides/python-net/id/aspose.slides.lowcode)
* pustaka [`Aspose.Slides`](/slides/python-net)