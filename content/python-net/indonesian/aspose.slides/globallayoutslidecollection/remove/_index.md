---
title: remove method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/globallayoutslidecollection/remove/
weight: 40
---
## remove(self, value) {#ilayoutslide}
Menghapus tata letak dari koleksi.

```python
def remove(self, value):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide) | Slide tata letak yang akan dihapus dari koleksi. |

### Catatan

1) Untuk menghindari terlemparnya PptxEditException, periksa properti HasDependingSlides pada tata letak terlebih dahulu.  
2) Anda juga dapat menggunakan metode [`ILayoutSlide.remove`](/slides/python-net/id/aspose.slides/ilayoutslide/remove) untuk menyederhanakan kode.

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception) | Dilemparkan jika tata letak digunakan dalam presentasi (properti HasDependingSlides bernilai true). |

### Lihat Juga
* kelas [`GlobalLayoutSlideCollection`](/slides/python-net/id/aspose.slides/globallayoutslidecollection)
* kelas [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide)
* kelas [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)