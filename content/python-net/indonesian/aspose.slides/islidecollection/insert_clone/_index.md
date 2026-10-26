---
title: insert_clone method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Menyisipkan salinan slide tertentu ke posisi yang ditentukan dalam koleksi.

### Mengembalikan

Slide yang disisipkan.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks slide baru. |
| source_slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | Slide untuk digandakan. |

### Catatan

Saat menyalin slide antar presentasi yang berbeda, master slide juga dapat disalin.
Internal registry digunakan untuk melacak master yang disalin secara otomatis guna mencegah pembuatan duplikat master slide yang sama.
Penyalinan manual master slide tidak akan dicegah maupun tercatat.
Jika Anda memerlukan kontrol lebih besar atas proses penyalinan, gunakan
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** atau
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** untuk menyalin slide dan
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** untuk menyalin master.


## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Menyisipkan salinan slide tertentu ke posisi yang ditentukan dalam koleksi.

### Mengembalikan

Slide yang disisipkan.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks slide baru. |
| source_slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | Slide untuk digandakan. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide) | Slide tata letak untuk slide baru. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Menyisipkan salinan slide sumber tertentu ke posisi yang ditentukan dalam koleksi.
Appropriate layout will be selected automatically from the specified 
master (appropriate layout is the layout with the same Type or Name as 
of layout of the source slide). If there is no appropriate layout then
layout of the source slide will be cloned (if allowCloneMissingLayout 
is true) or PptxEditException will be thrown (if allowCloneMissingLayout
is false).

### Mengembalikan

Slide yang disisipkan.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks slide baru. |
| source_slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | Slide untuk digandakan. |
| dest_master | [`IMasterSlide`](/slides/python-net/id/aspose.slides/imasterslide) | Master slide untuk slide baru. |
| allow_clone_missing_layout | **bool** | Jika tidak ada tata letak yang sesuai dalam master yang ditentukan maka tata letak dari <br/><br/>            slide sumber akan disalin (jika allowCloneMissingLayout bernilai true) atau <br/><br/>            PptxEditException akan dilemparkan (jika allowCloneMissingLayout bernilai false). |

### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception) | Dilemparkan jika tidak ada tata letak yang sesuai dalam master yang ditentukan dan <br/>            allowCloneMissingLayout bernilai false. |



### Lihat Juga
* kelas [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide)
* kelas [`IMasterSlide`](/slides/python-net/id/aspose.slides/imasterslide)
* kelas [`ISlide`](/slides/python-net/id/aspose.slides/islide)
* kelas [`ISlideCollection`](/slides/python-net/id/aspose.slides/islidecollection)
* kelas [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)