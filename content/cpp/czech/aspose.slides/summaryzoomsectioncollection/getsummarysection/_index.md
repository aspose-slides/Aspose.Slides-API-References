---
title: GetSummarySection()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací prvek Summary Zoom Section pro danou sekci.
type: docs
weight: 92
url: /cs/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) metoda

Vrací prvek Summary Zoom [Section](../../section/) pro zadanou sekci.

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) k nalezení [ISection](../../isection/) |

### Návratová hodnota

[ISummaryZoomSection](../../isummaryzoomsection/) nebo null, pokud kolekce neobsahuje prvek pro sekci.

## Poznámky

Příklad ukazuje získání prvku Summary Zoom [Section](../../section/) podle indexu:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISummaryZoomSection](../../isummaryzoomsection/)
* Třída [ISection](../../isection/)
* Třída [SummaryZoomSectionCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)