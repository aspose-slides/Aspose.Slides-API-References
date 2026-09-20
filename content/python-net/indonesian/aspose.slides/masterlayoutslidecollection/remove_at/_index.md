---
title: remove_at method
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Menghapus elemen pada indeks yang ditentukan dalam koleksi.

```python
def remove_at(self, index):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks berbasis nol dari elemen yang akan dihapus. |

### Catatan

1) Untuk menghindari munculnya PptxEditException, periksa properti HasDependingSlides pada layout terlebih dahulu.
2) Anda juga dapat menggunakan metode [`ILayoutSlide.remove`](/slides/python-net/id/aspose.slides/ilayoutslide/remove) untuk menyederhanakan kode.

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception) | Dilemparkan jika layout digunakan dalam presentasi (properti HasDependingSlides bernilai true). |

### Lihat Juga
* kelas [`MasterLayoutSlideCollection`](/slides/python-net/id/aspose.slides/masterlayoutslidecollection)
* kelas [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)