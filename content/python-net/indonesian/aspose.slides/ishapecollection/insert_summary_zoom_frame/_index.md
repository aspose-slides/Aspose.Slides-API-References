---
title: insert_summary_zoom_frame method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ishapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Membuat bingkai Summary Zoom baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

### Mengembalikan

[`ISummaryZoomFrame`](/slides/python-net/id/aspose.slides/isummaryzoomframe) yang baru dibuat.

```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol tempat menyisipkan bingkai Summary Zoom. |
| x | **float** | Koordinat x bingkai Summary Zoom yang baru, dalam poin. |
| y | **float** | Koordinat y bingkai Summary Zoom yang baru, dalam poin. |
| width | **float** | Lebar bingkai Summary Zoom yang baru, dalam poin. |
| height | **float** | Tinggi bingkai Summary Zoom yang baru, dalam poin. |

### Catatan

Metode ini membuat bingkai Summary Zoom yang menggabungkan tautan rangkuman untuk semua bagian dalam presentasi.

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception) | Dilemparkan jika presentasi tidak berisi bagian apa pun, atau jika slide target tidak termasuk dalam bagian mana pun. |

### Lihat Juga
* kelas [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection)
* kelas [`ISummaryZoomFrame`](/slides/python-net/id/aspose.slides/isummaryzoomframe)
* kelas [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)