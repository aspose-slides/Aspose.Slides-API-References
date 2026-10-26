---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Usuwa obiekt Summary Zoom Section z kolekcji.
type: docs
weight: 40
url: /pl/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) metoda

Usuń obiekt Summary Zoom [Section](../../section/) z kolekcji.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) dla którego element Summary Zoom [Section](../../section/) ma zostać usunięty [ISection](../../isection/). |

## Uwagi

Przykład pokazuje pobieranie elementu Summary Zoom [Section](../../section/) według indeksu:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISection](../../isection/)
* Klasa [ISummaryZoomSectionCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)