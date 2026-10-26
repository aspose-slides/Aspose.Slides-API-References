---
title: AddClone()
second_title: Aspose.Slides untuk Referensi API C++
description: Menambahkan salinan slide tata letak yang ditentukan ke presentasi.
type: docs
weight: 1
url: /id/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method

Menambahkan salinan slide tata letak yang ditentukan ke presentasi.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) untuk diklon. |

### Nilai Kembalian

Added slide.

## Catatan

Saat mengkloning tata letak antara presentasi yang berbeda, master tata letak juga dapat diklon untuk mempertahankan format sumber. Registri internal digunakan untuk melacak master yang diklon secara otomatis guna mencegah pembuatan beberapa klon dari slide master yang sama. Pengklonan manual slide master tidak akan dicegah maupun didaftarkan. 

## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) method

Menambahkan salinan slide tata letak yang ditentukan ke presentasi.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) untuk diklon. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Slide master untuk tata letak baru. |

### Nilai Kembalian

Added slide.

## Catatan

Tata letak baru akan terhubung dengan master yang ditentukan dalam presentasi tujuan. Jadi ini merupakan analogi dari salin/tempel dengan opsi "Use Destination Theme" di PowerPoint. 

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ILayoutSlide](../../ilayoutslide/)
* Kelas [IGlobalLayoutSlideCollection](../)
* Kelas [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)