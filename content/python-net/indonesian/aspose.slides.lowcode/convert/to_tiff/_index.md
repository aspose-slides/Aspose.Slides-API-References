---
title: to_tiff method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
Mengonversi presentasi input menjadi sekumpulan gambar berformat TIFF.  
            Jika nama berkas output diberikan sebagai "myPath/myFilename.tiff", hasil akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.tiff", di mana N adalah nomor slide.


```python
@staticmethod
def to_tiff(pres, output_file_name):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/id/aspose.slides/presentation) | Presentasi input. |
| output_file_name | **str** | Nama berkas output. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
Mengonversi presentasi input ke format TIFF dengan opsi khusus.
            Jika nama berkas output diberikan sebagai "myPath/myFilename.tiff" dan `multipage` bernilai `false`, hasil akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.tiff", di mana N adalah nomor slide.
            Jika tidak, jika `multipage` bernilai `true`, hasil akan menjadi dokumen "myPath/myFilename.tiff" multi-halaman.


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/id/aspose.slides/presentation) | Presentasi input. |
| output_file_name | **str** | Nama berkas output. |
| options | [`ITiffOptions`](/slides/python-net/id/aspose.slides.export/itiffoptions) | Opsi penyimpanan TIFF. |
| multipage | **bool** | Menentukan apakah dokumen TIFF yang dihasilkan harus berupa multi-halaman. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Lihat Juga
* kelas [`Convert`](/slides/python-net/id/aspose.slides.lowcode/convert)
* kelas [`ITiffOptions`](/slides/python-net/id/aspose.slides.export/itiffoptions)
* kelas [`Presentation`](/slides/python-net/id/aspose.slides/presentation)
* modul [`aspose.slides.lowcode`](/slides/python-net/id/aspose.slides.lowcode)
* perpustakaan [`Aspose.Slides`](/slides/python-net)