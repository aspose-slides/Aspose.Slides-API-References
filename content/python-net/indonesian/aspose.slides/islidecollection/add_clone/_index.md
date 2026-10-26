---
title: add_clone method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Menambahkan salinan slide yang ditentukan ke akhir koleksi.

### Mengembalikan

Slide baru.



```python
def add_clone(self, source_slide):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | Slide to clone. |

### Catatan

Saat men-clone sebuah slide antar presentasi yang berbeda, master slide juga dapat di-clone too.
Internal registry is used to track automatically cloned masters to prevent creation of 
multiple clones of the same master slide.
Manual cloning of master slides will be neither prevented nor registered.
If you need more control over cloning process use
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** or
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** for cloning slides,
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** or
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** for cloning layouts and
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** for cloning masters.


## add_clone(self, source_slide, section) {#islide-isection}
Menambahkan salinan slide yang ditentukan ke akhir bagian yang ditentukan.

### Mengembalikan

Slide baru.



```python
def add_clone(self, source_slide, section):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | Slide to clone. |
| section | [`ISection`](/slides/python-net/id/aspose.slides/isection) | Section for a new slide. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Menambahkan salinan slide yang ditentukan ke akhir koleksi.

### Mengembalikan

Slide baru.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | Slide to clone. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide) | Layout slide for a new slide. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Menambahkan salinan slide sumber yang ditentukan ke akhir koleksi. Appropriate layout will be selected automatically from the specified 
master (appropriate layout is the layout with the same Type or Name as 
of layout of the source slide). If there is no appropriate layout then
layout of the source slide will be cloned (if allowCloneMissingLayout 
is true) or PptxEditException will be thrown (if allowCloneMissingLayout
is false).

### Mengembalikan

Slide baru.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | Slide to clone. |
| dest_master | [`IMasterSlide`](/slides/python-net/id/aspose.slides/imasterslide) | Master slide for a new slide. |
| allow_clone_missing_layout | **bool** | Jika tidak ada layout yang sesuai dalam master yang ditentukan maka layout dari <br/><br/>            slide sumber akan di-clone (jika allowCloneMissingLayout bernilai true) atau <br/><br/>            PptxEditException akan dilempar (jika allowCloneMissingLayout bernilai false). |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception) | Dilempar jika tidak ada layout yang sesuai dalam master yang ditentukan dan <br/>            allowCloneMissingLayout bernilai false. |



### Lihat Juga
* kelas [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide)
* kelas [`IMasterSlide`](/slides/python-net/id/aspose.slides/imasterslide)
* kelas [`ISection`](/slides/python-net/id/aspose.slides/isection)
* kelas [`ISlide`](/slides/python-net/id/aspose.slides/islide)
* kelas [`ISlideCollection`](/slides/python-net/id/aspose.slides/islidecollection)
* kelas [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)