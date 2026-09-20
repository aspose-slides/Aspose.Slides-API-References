---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Membuat frame Summary Zoom baru dan memasukkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

### Mengembalikan

[`ISummaryZoomFrame`](/slides/python-net/id/aspose.slides/isummaryzoomframe) yang baru dibuat.

```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol tempat memasukkan frame Summary Zoom. |
| x | **float** | Koordinat x dari frame Summary Zoom baru, dalam poin. |
| y | **float** | Koordinat y dari frame Summary Zoom baru, dalam poin. |
| width | **float** | Lebar frame Summary Zoom baru, dalam poin. |
| height | **float** | Tinggi frame Summary Zoom baru, dalam poin. |

### Catatan

Metode ini membuat frame Summary Zoom yang menggabungkan tautan ringkasan untuk semua bagian dalam presentasi.

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception) | Dilempar jika presentasi tidak memiliki bagian, atau jika slide target tidak termasuk dalam bagian mana pun. |

### Lihat Juga
* kelas [`ISummaryZoomFrame`](/slides/python-net/id/aspose.slides/isummaryzoomframe)
* kelas [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception)
* kelas [`ShapeCollection`](/slides/python-net/id/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)