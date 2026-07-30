---
title: Clear()
second_title: Aspose.Slides pro C++ API Reference
description: Odstraňuje všechny objekty SummaryZoomSection ze sbírky.
type: docs
weight: 66
url: /cs/aspose.slides/isummaryzoomsectioncollection/clear/
---
## ISummaryZoomSectionCollection::Clear() metoda


Odstraňuje všechny objekty [SummaryZoomSection](../../summaryzoomsection/) ze sbírky.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::Clear()=0
```

## Poznámky


Příklad ukazuje, jak získat element Summary Zoom [Section](../../section/) podle indexu: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Viz také

* Třída [ISummaryZoomSectionCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)