---
title: remove method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ilayoutslide/remove/
weight: 60
---
## remove(self) {#}
Menghapus tata letak dari presentasi.

```python
def remove(self):
    ...
```

### Catatan

Untuk menghindari PptxEditException, periksa properti HasDependingSlides milik layout terlebih dahulu.

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception) | Dilempar jika tata letak sudah dihapus dari presentasi atau jika tata letak digunakan dalam presentasi (properti HasDependingSlides-nyanya <br/> bernilai true). |

### Lihat Juga
* class [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide)
* class [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)