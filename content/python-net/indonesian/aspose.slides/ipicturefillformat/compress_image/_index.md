---
title: compress_image method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Mengompresi gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. Secara opsional, juga menghapus area yang dipotong.

### Mengembalikan

Sebuah **bool** yang menunjukkan apakah gambar berhasil dikompresi. Mengembalikan **True** jika gambar diubah ukurannya atau dipotong, bila tidak **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Jika true, metode akan menghapus area yang dipotong dari gambar, yang berpotensi lebih mengurangi ukurannya. |
| resolution | [`PicturesCompression`](/slides/python-net/id/aspose.slides.export/picturescompression) | Resolusi target untuk kompresi, ditentukan sebagai nilai dari enum [`PicturesCompression`](/slides/python-net/id/aspose.slides.export/picturescompression). |

### Catatan

Metode ini mengubah ukuran dan resolusi gambar mirip dengan fitur "Picture Format -> Compress Pictures" di PowerPoint.

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilempar ketika resolusi tidak merupakan nilai yang valid. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Mengompresi gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. Secara opsional, juga menghapus area yang dipotong.

### Mengembalikan

Sebuah **bool** yang menunjukkan apakah gambar berhasil dikompresi. Mengembalikan **True** jika gambar diubah ukurannya atau dipotong, bila tidak **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Jika true, metode akan menghapus area yang dipotong dari gambar, yang berpotensi lebih mengurangi ukurannya. |
| resolution | **float** | Resolusi target dalam DPI. Nilai ini harus positif dan menentukan bagaimana gambar akan diubah ukurannya. |

### Catatan

Metode ini mengubah ukuran dan resolusi gambar mirip dengan fitur "Picture Format -> Compress Pictures" di PowerPoint.

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Dilempar ketika resolusi tidak merupakan nilai positif. |



### Lihat Juga
* kelas [`IPictureFillFormat`](/slides/python-net/id/aspose.slides/ipicturefillformat)
* enumerasi [`PicturesCompression`](/slides/python-net/id/aspose.slides.export/picturescompression)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)