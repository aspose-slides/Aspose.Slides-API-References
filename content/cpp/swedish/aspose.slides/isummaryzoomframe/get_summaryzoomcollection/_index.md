---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar ISummaryZoomSectionCollection för Summary Zoom Frame-objektet.
type: docs
weight: 14
url: /sv/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() metod

Hämtar [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) för Summary Zoom Frame-objektet.

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## Anmärkningar

Exemplet visar hur man hämtar Summary Zoom [Section](../../section/)-elementet med index:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Klass [ISummaryZoomFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)