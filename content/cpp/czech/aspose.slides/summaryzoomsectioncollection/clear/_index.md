---
title: Clear()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Odstraní všechny objekty SummaryZoomSection ze sbírky.
type: docs
weight: 105
url: /cs/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() metoda


Odstraňuje všechny [SummaryZoomSection](../../summaryzoomsection/) objekty ze sbírky.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## Poznámky


Příklad ukazuje získání prvku Summary Zoom [Section](../../section/) podle indexu: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Viz také

* Třída [SummaryZoomSectionCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)