---
title: AddSummaryZoomSection()
second_title: Aspose.Slides pro C++ referenci API
description: Vytvoří nový objekt Summary Zoom Section a přidá jej do kolekce
type: docs
weight: 14
url: /cs/aspose.slides/isummaryzoomsectioncollection/addsummaryzoomsection/
---
## ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) metoda

Vytváří nový objekt Summary Zoom [Section](../../section/) a přidá jej do kolekce

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) pro nový Summary Zoom [Section](../../section/) prvek [ISection](../../isection/) |

### Návratová hodnota

Přidaný [ISummaryZoomFrame](../../isummaryzoomframe/) prvek
## Poznámky

Pokud již v kolekci existuje prvek pro tento oddíl, vrátí se existující prvek.

Příklad ukazuje získání Summary Zoom [Section](../../section/) prvku podle indexu:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISummaryZoomSection](../../isummaryzoomsection/)
* Třída [ISection](../../isection/)
* Třída [ISummaryZoomSectionCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)