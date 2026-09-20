---
title: remove method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/masterlayoutslidecollection/remove/
weight: 60
---
## remove(self, value) {#ilayoutslide}
Menghapus layout dari koleksi.

```python
def remove(self, value):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide) | Slide tata letak yang akan dihapus dari koleksi. |

### Catatan

1) Untuk menghindari pengecualian PptxEditException, periksa properti HasDependingSlides pada layout terlebih dahulu.  
2) Anda juga dapat menggunakan metode [`ILayoutSlide.remove`](/slides/python-net/id/aspose.slides/ilayoutslide/remove) untuk menyederhanakan kode.

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception) | Dilemparkan jika layout digunakan dalam presentasi (properti HasDependingSlides-nya bernilai true). |

### Lihat Juga
* kelas [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide)
* kelas [`MasterLayoutSlideCollection`](/slides/python-net/id/aspose.slides/masterlayoutslidecollection)
* kelas [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)