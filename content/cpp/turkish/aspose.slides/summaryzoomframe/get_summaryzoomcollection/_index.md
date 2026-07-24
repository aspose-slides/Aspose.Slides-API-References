---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides for C++ API Referansı
description: Summary Zoom Frame nesnesi için ISummaryZoomSectionCollection alır.
type: docs
weight: 14
url: /tr/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() metod

Summary Zoom Frame nesnesi için [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) alır.

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## Açıklamalar

Örnek, indeks ile Summary Zoom [Section](../../section/) öğesini almayı gösterir:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Bkz.

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Class [SummaryZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)