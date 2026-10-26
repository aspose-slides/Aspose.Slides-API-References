---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides dla C++ – referencja API
description: Pobiera ISummaryZoomSectionCollection dla obiektu Summary Zoom Frame.
type: docs
weight: 14
url: /pl/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() metoda

Pobiera [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) dla obiektu Summary Zoom Frame.

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## Uwagi

Przykład demonstruje pobieranie elementu Summary Zoom [Section](../../section/) po indeksie:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* Klasa [SummaryZoomFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)