---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Pobiera ISummaryZoomSectionCollection dla obiektu Summary Zoom Frame.
type: docs
weight: 14
url: /pl/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() metoda

Pobiera [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) dla obiektu Summary Zoom Frame.

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## Uwagi

Przykład demonstruje pobieranie elementu Summary Zoom [Section](../../section/) według indeksu:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Klasa [ISummaryZoomFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)