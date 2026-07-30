---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides pro C++ API
description: Odstraní objekt Summary Zoom Section ze sbírky.
type: docs
weight: 79
url: /cs/aspose.slides/summaryzoomsectioncollection/removesummaryzoomsection/
---
## SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) metoda

Odstraňte objekt Summary Zoom [Section](../../section/) ze sbírky.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) pro který má být prvek Summary Zoom [Section](../../section/) odstraněn [ISection](../../isection/). |

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
* Třída [SummaryZoomSectionCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)