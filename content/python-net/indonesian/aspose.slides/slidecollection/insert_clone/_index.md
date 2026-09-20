---
title: insert_clone method
second_title: Aspose.Slides untuk Python melalui Referensi API .NET
description: 
type: docs
url: /id/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Menyisipkan salinan slide yang ditentukan ke posisi tertentu dalam koleksi.

### Mengembalikan

Slide yang disisipkan.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Index of new slide. |
| source_slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | Slide to clone. |

### Keterangan

Ketika menyalin slide antara presentasi yang berbeda, master slide dapat disalin juga.
            Registry internal digunakan untuk melacak master yang disalin secara otomatis guna mencegah pembuatan duplikat master slide yang sama.
            Penyalinan manual master slide tidak akan dicegah maupun didaftarkan.
            Jika Anda membutuhkan kontrol lebih besar atas proses penyalinan, gunakan
            **Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** atau
            **Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** untuk menyalin slide dan
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** untuk menyalin master.



## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Menyisipkan salinan slide yang ditentukan ke posisi tertentu dalam koleksi.

### Mengembalikan

Slide yang disisipkan.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Index of new slide. |
| source_slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | Slide to clone. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide) | Layout slide untuk slide baru. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Menyisipkan salinan slide sumber yang ditentukan ke posisi tertentu dalam koleksi.
            Layout yang sesuai akan dipilih secara otomatis dari master yang ditentukan
            (layout yang sesuai adalah layout dengan Type atau Name yang sama dengan
            layout slide sumber). Jika tidak ada layout yang sesuai maka
            layout slide sumber akan disalin (jika allowCloneMissingLayout
            bernilai true) atau PptxEditException akan dilempar (jika allowCloneMissingLayout
            bernilai false).

### Mengembalikan

Slide yang disisipkan.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Index of new slide. |
| source_slide | [`ISlide`](/slides/python-net/id/aspose.slides/islide) | Slide to clone. |
| dest_master | [`IMasterSlide`](/slides/python-net/id/aspose.slides/imasterslide) | Master slide for a new slide. |
| allow_clone_missing_layout | **bool** | Jika tidak ada layout yang sesuai dalam master yang ditentukan maka layout dari <br/><br/>            slide sumber akan disalin (jika allowCloneMissingLayout bernilai true) atau <br/><br/>            PptxEditException akan dilempar (jika allowCloneMissingLayout bernilai false). |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception) | Dilempar jika tidak ada layout yang sesuai dalam master yang ditentukan dan <br/>            allowCloneMissingLayout bernilai false. |



### Lihat Juga
* class [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide)
* class [`IMasterSlide`](/slides/python-net/id/aspose.slides/imasterslide)
* class [`ISlide`](/slides/python-net/id/aspose.slides/islide)
* class [`PptxEditException`](/slides/python-net/id/aspose.slides/pptxeditexception)
* class [`SlideCollection`](/slides/python-net/id/aspose.slides/slidecollection)
* module [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)