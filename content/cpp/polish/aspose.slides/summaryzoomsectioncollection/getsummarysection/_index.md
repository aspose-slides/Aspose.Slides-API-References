---
title: GetSummarySection()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Zwraca element Summary Zoom Section dla podanej sekcji.
type: docs
weight: 92
url: /pl/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) metoda

Zwraca element Summary Zoom [Section](../../section/) dla podanej sekcji.

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) aby znaleźć [ISection](../../isection/) |

### Wartość zwracana

[ISummaryZoomSection](../../isummaryzoomsection/) lub null, jeśli kolekcja nie zawiera elementu dla sekcji.

## Uwagi

Przykład pokazuje pobieranie elementu Summary Zoom [Section](../../section/) za pomocą indeksu:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISummaryZoomSection](../../isummaryzoomsection/)
* Klasa [ISection](../../isection/)
* Klasa [SummaryZoomSectionCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)