---
title: GetSummarySection()
second_title: Referencja API Aspose.Slides dla C++
description: Zwraca element Summary Zoom Section dla podanej sekcji.
type: docs
weight: 27
url: /pl/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---
## ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) metoda

Zwraca element Summary Zoom [Section](../../section/) dla podanej sekcji.

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) to find [ISection](../../isection/) |

### Wartość zwracana

[ISummaryZoomSection](../../isummaryzoomsection/) lub null, jeśli kolekcja nie zawiera elementu dla sekcji.

## Uwagi

Przykład pokazuje pobieranie elementu Summary Zoom [Section](../../section/) po indeksie:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [ISection](../../isection/)
* Class [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)