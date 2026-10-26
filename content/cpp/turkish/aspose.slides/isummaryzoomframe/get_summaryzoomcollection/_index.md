---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides for C++ API Referansı
description: Summary Zoom Frame nesnesi için ISummaryZoomSectionCollection alır.
type: docs
weight: 14
url: /tr/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() metodu

Alır [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) için Summary Zoom Frame nesnesi.

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## Açıklamalar

Örnek, indeksle Summary Zoom [Section](../../section/) öğesini almayı gösterir: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Sınıf [ISummaryZoomFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)