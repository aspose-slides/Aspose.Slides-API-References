---
title: idx_get()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan elemen pada indeks yang ditentukan. Hanya-baca ISummaryZoomSection.
type: docs
weight: 40
url: /id/aspose.slides/summaryzoomsectioncollection/idx_get/
---
## SummaryZoomSectionCollection::idx_get(int32_t) metode


Mendapatkan elemen pada indeks yang ditentukan. Hanya-baca [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::idx_get(int32_t index) override
```

## Catatan


Contoh ini menunjukkan cara mendapatkan elemen Summary Zoom [Section](../../section/) dengan indeks: 
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
* Kelas [SummaryZoomSectionCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)