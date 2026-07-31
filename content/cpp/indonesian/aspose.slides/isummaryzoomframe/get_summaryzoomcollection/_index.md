---
title: get_SummaryZoomCollection()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan ISummaryZoomSectionCollection untuk objek Summary Zoom Frame.
type: docs
weight: 14
url: /id/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() metode


Mendapatkan [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) untuk objek Summary Zoom Frame.

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## Catatan


Contoh ini mendemonstrasikan mendapatkan elemen Summary Zoom [Section](../../section/) berdasarkan indeks: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Kelas [ISummaryZoomFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)