---
title: remove method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/layoutslide/remove/
weight: 60
---
## remove(self) {#}
Menghapus tata letak dari presentasi.

```python
def remove(self):
    ...
```

### Catatan

Untuk menghindari terlemparnya PptxEditException, periksa properti HasDependingSlides dari layout terlebih dahulu.

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception) | Dilemparkan jika tata letak sudah dihapus dari presentasi atau jika tata letak digunakan dalam presentasi (properti HasDependingSlides <br/>            bernilai true). |

### Lihat Juga
* kelas [`LayoutSlide`](/slides/python-net/id/aspose.slides/layoutslide)
* kelas [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)