---
title: idx_get()
second_title: Aspose.Slides dla C++ Referencja API
description: Pobiera element pod określonym indeksem. Tylko do odczytu ISummaryZoomSection.
type: docs
weight: 40
url: /pl/aspose.slides/summaryzoomsectioncollection/idx_get/
---
## SummaryZoomSectionCollection::idx_get(int32_t) metoda

Pobiera element pod określonym indeksem. Tylko do odczytu [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::idx_get(int32_t index) override
```

## Uwagi

Przykład demonstruje pobieranie elementu Summary Zoom [Section](../../section/) po indeksie:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [ISummaryZoomSection](../../isummaryzoomsection/)
* Klasa [SummaryZoomSectionCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)