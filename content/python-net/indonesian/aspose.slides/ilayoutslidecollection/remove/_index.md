---
title: remove method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ilayoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
Menghapus layout dari koleksi.

```python
def remove(self, value):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide) | Layout slide yang akan dihapus dari koleksi. |

### Keterangan

1) Untuk menghindari terlemparnya PptxEditException, periksa properti HasDependingSlides pada layout terlebih dahulu.
2) Anda juga dapat menggunakan metode [`ILayoutSlide.remove`](/slides/python-net/id/aspose.slides/ilayoutslide/remove) untuk menyederhanakan kode.

### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception) | Dilemparkan jika layout digunakan dalam presentasi (properti HasDependingSlides bernilai true). |

### Lihat Juga
* kelas [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide)
* kelas [`ILayoutSlideCollection`](/slides/python-net/id/aspose.slides/ilayoutslidecollection)
* kelas [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)