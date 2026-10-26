---
title: add_clone method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/slidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Menambahkan salinan slide tertentu ke akhir koleksi.

### Returns
Slide baru.



```python
def add_clone(self, source_slide):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | Slide yang akan dikloning. |

### Catatan
Saat mengkloning slide antara presentasi yang berbeda, master slide juga dapat dikloning.
Registri internal digunakan untuk melacak master yang dikloning secara otomatis agar mencegah pembuatan beberapa klon dari master slide yang sama.
Kloning manual master slide tidak akan dicegah maupun didaftarkan.
Jika Anda memerlukan kontrol lebih atas proses kloning, gunakan
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** atau
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** untuk mengkloning slide,
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** atau
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** untuk mengkloning layout, dan
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** untuk mengkloning master.


## add_clone(self, source_slide, section) {#islide-isection}
Menambahkan salinan slide tertentu ke akhir bagian yang ditentukan.

### Mengembalikan
Slide baru.



```python
def add_clone(self, source_slide, section):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | Slide yang akan dikloning. |
| section | [`ISection`](/slides/python-net/id/aspose.slides/isection) | Bagian untuk slide baru. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Menambahkan salinan slide tertentu ke akhir koleksi.

### Mengembalikan
Slide baru.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | Slide yang akan dikloning. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide) | Layout slide untuk slide baru. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Menambahkan salinan slide sumber tertentu ke akhir koleksi.
Layout yang sesuai akan dipilih secara otomatis dari master yang ditentukan
(layout yang sesuai adalah layout dengan Type atau Name yang sama dengan layout dari slide sumber). Jika tidak ada layout yang sesuai maka
layout dari slide sumber akan dikloning (jika allowCloneMissingLayout
bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout
bernilai false).

### Mengembalikan
Slide baru.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | Slide yang akan dikloning. |
| dest_master | [`IMasterSlide`](/slides/python-net/id/aspose.slides/imasterslide) | Master slide untuk slide baru. |
| allow_clone_missing_layout | **bool** | Jika tidak ada layout yang sesuai dalam master yang ditentukan maka layout dari <br/><br/>            slide sumber akan dikloning (jika allowCloneMissingLayout bernilai true) atau <br/><br/>            PptxEditException akan dilempar (jika allowCloneMissingLayout bernilai false). |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception) | Dilempar jika tidak ada layout yang sesuai dalam master yang ditentukan dan <br/>            allowCloneMissingLayout bernilai false. |



### Lihat Juga
* kelas [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide)
* kelas [`IMasterSlide`](/slides/python-net/id/aspose.slides/imasterslide)
* kelas [`ISection`](/slides/python-net/id/aspose.slides/isection)
* kelas [`ISlide`](/slides/python-net/id/aspose.slides/islide)
* kelas [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception)
* kelas [`SlideCollection`](/slides/python-net/id/aspose.slides/slidecollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)