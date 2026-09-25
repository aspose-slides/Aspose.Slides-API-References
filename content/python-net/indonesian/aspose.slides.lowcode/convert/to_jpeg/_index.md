---
title: to_jpeg method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
Mengonversi presentasi input menjadi sekumpulan gambar berformat JPEG.  
            Jika nama file output diberikan sebagai "myPath/myFilename.jpeg", 
            hasilnya akan disimpan sebagai sekumpulan file "myPath/myFilename_N.jpeg", dimana N adalah nomor slide.


```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/id/aspose.slides/presentation) | Presentasi input. |
| output_file_name | **str** | Nama file output. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
Mengonversi presentasi input menjadi sekumpulan gambar berformat JPEG.  
            Jika nama file output diberikan sebagai "myPath/myFilename.jpeg", 
            hasilnya akan disimpan sebagai sekumpulan file "myPath/myFilename_N.jpeg", dimana N adalah nomor slide.


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/id/aspose.slides/presentation) | Presentasi input |
| output_file_name | **str** | Nama file output. |
| image_size | [`Size`](/slides/python-net/id/aspose.slides/size) | Ukuran setiap gambar yang dihasilkan. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Mengonversi presentasi input menjadi sekumpulan gambar berformat JPEG.  
            Jika nama file output diberikan sebagai "myPath/myFilename.jpeg", 
            hasilnya akan disimpan sebagai sekumpulan file "myPath/myFilename_N.jpeg", dimana N adalah nomor slide.


```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/id/aspose.slides/presentation) | Presentasi input. |
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
* library [`Aspose.Slides`](/slides/python-net)