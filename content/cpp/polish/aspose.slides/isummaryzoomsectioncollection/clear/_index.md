---
title: Clear()
second_title: Aspose.Slides dla C++ - Referencja API
description: Usuwa wszystkie obiekty SummaryZoomSection z kolekcji.
type: docs
weight: 66
url: /pl/aspose.slides/isummaryzoomsectioncollection/clear/
---
## ISummaryZoomSectionCollection::Clear() metoda


Usuwa wszystkie [SummaryZoomSection](../../summaryzoomsection/) obiekty z kolekcji.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::Clear()=0
```

## Uwagi


Przykład demonstruje pobieranie elementu Summary Zoom [Section](../../section/) po indeksie:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## Zobacz także

* Klasa [ISummaryZoomSectionCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)