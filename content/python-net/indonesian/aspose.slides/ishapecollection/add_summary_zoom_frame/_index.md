---
title: add_summary_zoom_frame method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ishapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
Membuat frame Summary Zoom baru dan menambahkannya ke akhir koleksi shape.

### Mengembalikan

[`ISummaryZoomFrame`](/slides/python-net/id/aspose.slides/isummaryzoomframe) yang baru dibuat.



```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | **float** | Koordinat x dari frame Summary Zoom baru, dalam poin. |
| y | **float** | Koordinat y dari frame Summary Zoom baru, dalam poin. |
| width | **float** | Lebar frame Summary Zoom baru, dalam poin. |
| height | **float** | Tinggi frame Summary Zoom baru, dalam poin. |

### Catatan

Metode ini membuat frame Summary Zoom yang menggabungkan tautan ringkasan untuk semua bagian dalam presentasi.

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception) | Dilemparkan jika tidak ada bagian dalam presentasi, atau jika slide target tidak termasuk dalam bagian mana pun. |



### Lihat Juga
* kelas [`IShapeCollection`](/slides/python-net/id/aspose.slides/ishapecollection)
* kelas [`ISummaryZoomFrame`](/slides/python-net/id/aspose.slides/isummaryzoomframe)
* kelas [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)