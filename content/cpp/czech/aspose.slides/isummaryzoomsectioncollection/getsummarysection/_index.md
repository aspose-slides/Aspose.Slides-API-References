---
title: GetSummarySection()
second_title: Aspose.Slides pro C++ referenci API
description: Vrací element Summary Zoom Section pro zadanou sekci.
type: docs
weight: 27
url: /cs/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---
## ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) metoda


Vrací Summary Zoom [Section](../../section/) element pro zadanou sekci.

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) k nalezení [ISection](../../isection/) |

### Návratová hodnota

[ISummaryZoomSection](../../isummaryzoomsection/) nebo null, pokud kolekce neobsahuje prvek pro sekci.
## Poznámky



Příklad ukazuje získání Summary Zoom [Section](../../section/) elementu podle indexu: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [ISummaryZoomSection](../../isummaryzoomsection/)
* Třída [ISection](../../isection/)
* Třída [ISummaryZoomSectionCollection](../)
* Prostor názvů [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)