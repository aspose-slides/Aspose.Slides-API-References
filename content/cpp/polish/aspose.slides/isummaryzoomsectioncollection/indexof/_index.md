---
title: IndexOf()
second_title: Aspose.Slides dla C++ Referencja API
description: Zwraca indeks określonego obiektu SummaryZoomSection.
type: docs
weight: 53
url: /pl/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) metoda

Zwraca indeks określonego [SummaryZoomSection](../../summaryzoomsection/) obiektu.

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) obiekt do znalezienia [ISummaryZoomSection](../../isummaryzoomsection/). |

### Wartość zwracana

Indeks obiektu [SummaryZoomSection](../../summaryzoomsection/) lub -1, jeśli obiekt [SummaryZoomSection](../../summaryzoomsection/) nie pochodzi z tej kolekcji.

## Uwagi

Przykład pokazuje pobieranie elementu Summary Zoom [Section](../../section/) za pomocą indeksu:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISummaryZoomSection](../../isummaryzoomsection/)
* Klasa [ISummaryZoomSectionCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)