---
title: insert_clone method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/imasterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Menyisipkan salinan slide tata letak tertentu ke posisi yang ditentukan dalam koleksi.

### Returns
Slide yang disisipkan.

```python
def insert_clone(self, index, source_layout):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | **int** | Indeks slide baru. |
| source_layout | [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide) | Slide yang akan digandakan. |

### Remarks
Tata letak baru akan terhubung dengan slide master induk untuk koleksi slide tata letak ini.  
Jadi ini merupakan analogi dari salin/tempel dengan opsi "Use Destination Theme" di PowerPoint.

### See Also
* kelas [`ILayoutSlide`](/slides/python-net/id/aspose.slides/ilayoutslide)
* kelas [`IMasterLayoutSlideCollection`](/slides/python-net/id/aspose.slides/imasterlayoutslidecollection)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)