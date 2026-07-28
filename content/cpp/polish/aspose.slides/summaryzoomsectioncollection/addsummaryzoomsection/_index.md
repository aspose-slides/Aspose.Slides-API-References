---
title: AddSummaryZoomSection()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy nowy obiekt Summary Zoom Section i dodaje go do kolekcji
type: docs
weight: 53
url: /pl/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) metoda


Tworzy nowy obiekt Summary Zoom [Section](../../section/) i dodaje go do kolekcji

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) dla nowego elementu Summary Zoom [Section](../../section/) [ISection](../../isection/) |

### Wartość zwracana

Dodano [ISummaryZoomFrame](../../isummaryzoomframe/) element

## Uwagi



Jeśli element dla tej sekcji już istnieje w kolekcji, zwracany jest istniejący element. 


Przykład demonstruje pobieranie elementu Summary Zoom [Section](../../section/) według indeksu: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [ISummaryZoomSection](../../isummaryzoomsection/)
* Klasa [ISection](../../isection/)
* Klasa [SummaryZoomSectionCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)