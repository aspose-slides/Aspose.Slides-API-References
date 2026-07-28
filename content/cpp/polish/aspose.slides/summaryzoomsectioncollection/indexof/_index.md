---
title: IndexOf()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Zwraca indeks określonego obiektu SummaryZoomSection.
type: docs
weight: 66
url: /pl/aspose.slides/summaryzoomsectioncollection/indexof/
---
## SummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) metoda

Zwraca indeks określonego obiektu [SummaryZoomSection](../../summaryzoomsection/).

```cpp
int32_t Aspose::Slides::SummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | obiekt [SummaryZoomSection](../../summaryzoomsection/) do znalezienia [ISummaryZoomSection](../../isummaryzoomsection/). |

### Wartość zwracana

Indeks obiektu [SummaryZoomSection](../../summaryzoomsection/) lub -1, jeśli obiekt [SummaryZoomSection](../../summaryzoomsection/) nie pochodzi z tej kolekcji.

## Uwagi

Przykład demonstruje pobieranie elementu Summary Zoom [Section](../../section/) według indeksu:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## Zobacz też

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISummaryZoomSection](../../isummaryzoomsection/)
* Klasa [SummaryZoomSectionCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)