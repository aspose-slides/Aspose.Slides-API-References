---
title: AddClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan salinan slide tata letak yang ditentukan ke akhir koleksi.
type: docs
weight: 1
url: /id/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metode

Menambahkan salinan slide tata letak yang ditentukan ke akhir koleksi.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) to clone. |

### Nilai Kembali

Slide yang ditambahkan.

## Catatan

1) Tata letak baru akan terhubung dengan slide master induk untuk koleksi slide tata letak ini. Jadi ini merupakan analogi dari salin/tempel dengan opsi "Use Destination Theme" di PowerPoint. 2) Analogi dari metode ini adalah metode [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) yang diakses melalui properti [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ILayoutSlide](../../ilayoutslide/)
* Kelas [IMasterLayoutSlideCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)