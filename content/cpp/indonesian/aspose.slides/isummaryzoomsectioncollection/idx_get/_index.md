---
title: idx_get()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil elemen pada indeks yang ditentukan. Hanya-baca ISummaryZoomSection.
type: docs
weight: 1
url: /id/aspose.slides/isummaryzoomsectioncollection/idx_get/
---
## ISummaryZoomSectionCollection::idx_get(int32_t) metode

Mendapatkan elemen pada indeks yang ditentukan. Hanya-baca [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::idx_get(int32_t index)=0
```

## Catatan

Contoh ini menunjukkan cara mendapatkan elemen Summary Zoom [Section](../../section/) berdasarkan indeks: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISummaryZoomSection](../../isummaryzoomsection/)
* Kelas [ISummaryZoomSectionCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)