---
title: add_clone method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Menambahkan salinan slide tata letak yang ditentukan ke presentasi.

### Mengembalikan

Slide yang ditambahkan.



```python
def add_clone(self, source_layout):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide) | Slide yang akan dikloning. |

### Catatan

Saat mengkloning tata letak antara presentasi yang berbeda, master tata letak juga dapat dikloning untuk mempertahankan format sumber.            Registri internal digunakan untuk melacak master yang dikloning secara otomatis guna mencegah pembuatan beberapa klon master slide yang sama.            Kloning manual master slide tidak akan dicegah maupun didaftarkan.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Menambahkan salinan slide tata letak yang ditentukan ke presentasi.

### Mengembalikan

Slide yang ditambahkan.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide) | Slide yang akan dikloning. |
| dest_master | [`IMasterSlide`](/slides/python-net/id/aspose.slides/imasterslide) | Master slide untuk tata letak baru. |

### Catatan

1) Tata letak baru akan dihubungkan dengan master yang ditentukan dalam presentasi tujuan.            Jadi ini merupakan analogi copy/paste dengan opsi "Use Destination Theme" di PowerPoint.            2) Analogi metode ini adalah metode **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide** yang diakses melalui properti [`IMasterSlide.layout_slides`](/slides/python-net/id/aspose.slides/imasterslide/layout_slides).



### Lihat Juga
* kelas [`GlobalLayoutSlideCollection`](/slides/python-net/id/aspose.slides/globallayoutslidecollection)
* kelas [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide)
* kelas [`IMasterSlide`](/slides/python-net/id/aspose.slides/imasterslide)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)