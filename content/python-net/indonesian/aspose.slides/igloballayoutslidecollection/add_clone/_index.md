---
title: add_clone method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Menambahkan salinan slide tata letak tertentu ke presentasi.

### Mengembalikan

Slide yang ditambahkan.



```python
def add_clone(self, source_layout):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide) | Slide untuk dikloning. |

### Catatan
When cloning a layout between different presentations layout's master can be cloned too
            untuk mempertahankan pemformatan sumber.
            Registri internal digunakan untuk melacak master yang dikloning secara otomatis guna mencegah pembuatan 
            beberapa klon dari slide master yang sama.
            Kloning manual slide master tidak akan dicegah maupun terdaftar.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Menambahkan salinan slide tata letak tertentu ke presentasi.

### Mengembalikan

Slide yang ditambahkan.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide) | Slide untuk dikloning. |
| dest_master | [`IMasterSlide`](/slides/python-net/id/aspose.slides/imasterslide) | Slide master untuk tata letak baru. |

### Catatan
Tata letak baru akan terhubung dengan master yang ditentukan dalam presentasi tujuan.
            Jadi ini adalah analogi dari salin/tempel dengan opsi "Use Destination Theme" di PowerPoint.



### Lihat Juga
* kelas [`IGlobalLayoutSlideCollection`](/slides/python-net/id/aspose.slides/igloballayoutslidecollection)
* kelas [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide)
* kelas [`IMasterSlide`](/slides/python-net/id/aspose.slides/imasterslide)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)