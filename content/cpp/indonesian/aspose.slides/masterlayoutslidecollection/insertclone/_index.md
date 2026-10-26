---
title: InsertClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyisipkan salinan slide tata letak tertentu ke posisi yang ditentukan dalam koleksi.
type: docs
weight: 14
url: /id/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) metode


Menyisipkan salinan slide tata letak tertentu ke posisi yang ditentukan dalam koleksi.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks slide baru. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) untuk digandakan. |

### Nilai Kembali

Slide yang disisipkan.
## Keterangan



Tata letak baru akan terhubung dengan slide master induk untuk koleksi slide tata letak ini. Jadi ini merupakan analogi copy/paste dengan opsi "Use Destination Theme" di PowerPoint. 

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ILayoutSlide](../../ilayoutslide/)
* Kelas [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)