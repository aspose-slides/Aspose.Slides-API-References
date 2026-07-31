---
title: get_SummaryZoomCollection()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan ISummaryZoomSectionCollection untuk objek Summary Zoom Frame.
type: docs
weight: 14
url: /id/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() metode

Mendapatkan [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) untuk objek Summary Zoom Frame.

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## Catatan

Contoh ini menunjukkan cara mendapatkan elemen Summary Zoom [Section](../../section/) berdasarkan indeks: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Kelas [SummaryZoomFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)