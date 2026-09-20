---
title: remove_at method
second_title: Aspose.Slides untuk Python melalui Referensi API .NET
description: 
type: docs
url: /id/aspose.slides/imasterlayoutslidecollection/remove_at/
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

1) Untuk menghindari lemparan PptxEditException, periksa properti HasDependingSlides dari layout terlebih dahulu.
2) Anda juga dapat menggunakan metode [`ILayoutSlide.remove`](/slides/python-net/id/aspose.slides/ilayoutslide/remove) untuk menyederhanakan kode.

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception) | Dilempar jika layout digunakan dalam presentasi (properti HasDependingSlides-nya bernilai true). |



### Lihat Juga
* kelas [`IMasterLayoutSlideCollection`](/slides/python-net/id/aspose.slides/imasterlayoutslidecollection)
* kelas [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)