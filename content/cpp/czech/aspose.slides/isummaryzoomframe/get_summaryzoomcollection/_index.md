---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides pro C++ API Reference
description: Získá ISummaryZoomSectionCollection pro objekt Summary Zoom Frame.
type: docs
weight: 14
url: /cs/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() metoda

Získá [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) pro objekt Summary Zoom Frame.

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## Poznámky

Příklad ukazuje získání elementu Summary Zoom [Section](../../section/) podle indexu:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Třída [ISummaryZoomFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)