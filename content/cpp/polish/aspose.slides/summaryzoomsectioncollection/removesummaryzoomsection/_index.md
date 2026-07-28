---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides dla C++ – Referencja API
description: Usuwa obiekt Summary Zoom Section z kolekcji.
type: docs
weight: 79
url: /pl/aspose.slides/summaryzoomsectioncollection/removesummaryzoomsection/
---
## SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) metoda

Usuń obiekt Summary Zoom [Section](../../section/) z kolekcji.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) dla którego element Summary Zoom [Section](../../section/) ma zostać usunięty [ISection](../../isection/). |

## Uwagi

Przykład pokazuje pobieranie elementu Summary Zoom [Section](../../section/) po indeksie:
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
* Klasa [SummaryZoomSectionCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)