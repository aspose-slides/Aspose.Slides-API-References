---
title: AddSummaryZoomSection()
second_title: Referencja API Aspose.Slides dla C++
description: Tworzy nowy obiekt Summary Zoom Section i dodaje go do kolekcji
type: docs
weight: 14
url: /pl/aspose.slides/isummaryzoomsectioncollection/addsummaryzoomsection/
---
## ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) metoda

Tworzy nowy obiekt Summary Zoom [Section](../../section/) i dodaje go do kolekcji

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) dla nowego Summary Zoom [Section](../../section/) element [ISection](../../isection/) |

### Wartość zwracana

Dodany [ISummaryZoomFrame](../../isummaryzoomframe/) element

## Uwagi

Jeśli element dla tej sekcji już istnieje w kolekcji, zwracany jest istniejący element. 

Przykład pokazuje pobieranie elementu Summary Zoom [Section](../../section/) po indeksie: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISummaryZoomSection](../../isummaryzoomsection/)
* Klasa [ISection](../../isection/)
* Klasa [ISummaryZoomSectionCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)