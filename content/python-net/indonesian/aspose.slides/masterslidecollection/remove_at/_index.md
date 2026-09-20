---
title: remove_at method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/masterslidecollection/remove_at/
weight: 40
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

### Keterangan

Untuk menghindari lemparan PptxEditException, periksa properti HasDependingSlides milik master terlebih dahulu.

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception) | Dilemparkan jika master yang akan dihapus digunakan dalam presentasi (properti HasDependingSlides-nya bernilai true). |

### Lihat Juga
* kelas [`MasterSlideCollection`](/slides/python-net/id/aspose.slides/masterslidecollection)
* kelas [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)