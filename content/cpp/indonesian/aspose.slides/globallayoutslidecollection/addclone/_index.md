---
title: AddClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan salinan slide tata letak yang ditentukan ke presentasi.
type: docs
weight: 1
url: /id/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metode


Menambahkan salinan slide tata letak yang ditentukan ke presentasi.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) untuk digandakan. |

### Nilai Kembali

Slide yang ditambahkan.

## Catatan



Saat menyalin tata letak antara presentasi yang berbeda, master tata letak juga dapat disalin untuk mempertahankan format sumber. Registri internal digunakan untuk melacak master yang disalin secara otomatis guna mencegah pembuatan salinan ganda dari master slide yang sama. Penyalinan master slide secara manual tidak akan dicegah maupun didaftarkan. 

## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) metode


Menambahkan salinan slide tata letak yang ditentukan ke presentasi.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) untuk digandakan. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master slide untuk tata letak baru. |

### Nilai Kembali

Slide yang ditambahkan.

## Catatan



1) Tata letak baru akan terhubung dengan master yang ditentukan dalam presentasi tujuan. Jadi ini analog dengan menyalin/tempel menggunakan opsi "Use Destination Theme" di PowerPoint. 2) Analog dari metode ini adalah metode [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) yang diakses dengan properti [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/). 

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [GlobalLayoutSlideCollection](../)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)