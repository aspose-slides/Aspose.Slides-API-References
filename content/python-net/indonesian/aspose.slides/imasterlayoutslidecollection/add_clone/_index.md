---
title: add_clone method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/imasterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Menambahkan salinan slide tata letak yang ditentukan ke akhir koleksi.

### Mengembalikan

Slide yang ditambahkan.



```python
def add_clone(self, source_layout):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide) | Slide yang akan dikloning. |

### Keterangan

1) Layout baru akan ditautkan dengan slide master induk untuk koleksi slide layout ini.
            Jadi ini merupakan analog dari copy/paste dengan opsi "Use Destination Theme" di PowerPoint.
            2) Analogi dari metode ini adalah metode **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide**
            diakses dengan properti [`IPresentation.layout_slides`](/slides/python-net/id/aspose.slides/ipresentation/layout_slides).



### Lihat Juga
* kelas [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide)
* kelas [`IMasterLayoutSlideCollection`](/slides/python-net/id/aspose.slides/imasterlayoutslidecollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)