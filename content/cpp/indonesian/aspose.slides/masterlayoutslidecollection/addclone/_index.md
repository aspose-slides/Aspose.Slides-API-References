---
title: AddClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan salinan slide tata letak yang ditentukan ke akhir koleksi.
type: docs
weight: 1
url: /id/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metode

Menambahkan salinan slide tata letak yang ditentukan ke akhir koleksi.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) untuk diklon. |

### Nilai Kembalian

Slide ditambahkan.

## Keterangan

1) Tata letak baru akan dihubungkan dengan slide master induk untuk koleksi slide tata letak ini. Jadi ini adalah analogi dari copy/paste dengan opsi "Use Destination Theme" di PowerPoint. 2) Analogi dari metode ini adalah metode [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) yang diakses dengan properti [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ILayoutSlide](../../ilayoutslide/)
* Kelas [MasterLayoutSlideCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)