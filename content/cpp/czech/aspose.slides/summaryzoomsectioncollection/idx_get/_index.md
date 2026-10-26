---
title: idx_get()
second_title: Aspose.Slides pro C++ API Reference
description: Získá prvek na zadaném indexu. Pouze ke čtení ISummaryZoomSection.
type: docs
weight: 40
url: /cs/aspose.slides/summaryzoomsectioncollection/idx_get/
---
## SummaryZoomSectionCollection::idx_get(int32_t) metoda


Získá prvek na určeném indexu. Pouze ke čtení [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::idx_get(int32_t index) override
```

## Poznámky


Příklad ukazuje, jak získat prvek Summary Zoom [Section](../../section/) podle indexu:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [ISummaryZoomSection](../../isummaryzoomsection/)
* Třída [SummaryZoomSectionCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)