---
title: compress_image method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Mengecilkan gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. Secara opsional, juga menghapus area yang dipotong.

### Mengembalikan
Sebuah **bool** yang menunjukkan apakah gambar berhasil dikompresi. Mengembalikan **True** jika gambar diubah ukurannya atau dipotong, jika tidak **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Jika true, metode akan menghapus area yang dipotong dari gambar, yang dapat mengurangi ukurannya lebih jauh. |
| resolution | [`PicturesCompression`](/slides/python-net/id/aspose.slides.export/picturescompression) | Resolusi target untuk kompresi, ditentukan sebagai nilai dari enum [`PicturesCompression`](/slides/python-net/id/aspose.slides.export/picturescompression). |

### Keterangan
Metode ini mengubah ukuran dan resolusi gambar mirip dengan fitur PowerPoint "Picture Format -> Compress Pictures".

### Pengecualian
| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan ketika resolusi bukan nilai yang valid. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Mengecilkan gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. Secara opsional, juga menghapus area yang dipotong.

### Mengembalikan
Sebuah **bool** yang menunjukkan apakah gambar berhasil dikompresi. Mengembalikan **True** jika gambar diubah ukurannya atau dipotong, jika tidak **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Jika true, metode akan menghapus area yang dipotong dari gambar, yang dapat mengurangi ukurannya lebih jauh. |
| resolution | **float** | Resolusi target dalam DPI. Nilai ini harus positif dan menentukan bagaimana gambar akan diubah ukurannya. |

### Keterangan
Metode ini mengubah ukuran dan resolusi gambar mirip dengan fitur PowerPoint "Picture Format -> Compress Pictures".

### Pengecualian
| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilemparkan ketika resolusi bukan nilai positif. |



### Lihat Juga
* kelas [`PictureFillFormat`](/slides/python-net/id/aspose.slides/picturefillformat)
* enumerasi [`PicturesCompression`](/slides/python-net/id/aspose.slides.export/picturescompression)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)