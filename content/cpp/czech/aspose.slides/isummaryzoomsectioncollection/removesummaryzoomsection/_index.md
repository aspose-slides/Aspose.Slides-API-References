---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Odstraňuje objekt Summary Zoom Section ze sbírky.
type: docs
weight: 40
url: /cs/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) metoda

Odstraňte objekt Summary Zoom [Section](../../section/) ze sbírky.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/), pro který má být odstraněn prvek Summary Zoom [Section](../../section/) [ISection](../../isection/). |

## Poznámky

Příklad ukazuje získání prvku Summary Zoom [Section](../../section/) podle indexu:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISection](../../isection/)
* Třída [ISummaryZoomSectionCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)