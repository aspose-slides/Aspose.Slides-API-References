---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Získá ISummaryZoomSectionCollection pro objekt Summary Zoom Frame.
type: docs
weight: 14
url: /cs/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() metoda


Získá [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) pro objekt Summary Zoom Frame.

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
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
* Třída [SummaryZoomFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)