---
title: InsertClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyisipkan salinan slide tata letak tertentu ke posisi yang ditentukan dalam koleksi.
type: docs
weight: 14
url: /id/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) metode

Menyisipkan salinan slide tata letak tertentu ke posisi yang ditentukan dalam koleksi.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks slide baru. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) untuk diklon. |

### Nilai Kembali

Slide yang dimasukkan.

## Catatan

Layout baru akan terhubung dengan slide master induk untuk koleksi slide tata letak ini. Jadi ini merupakan analogi dari salin/tempel dengan opsi "Use Destination Theme" di PowerPoint.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ILayoutSlide](../../ilayoutslide/)
* Kelas [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)