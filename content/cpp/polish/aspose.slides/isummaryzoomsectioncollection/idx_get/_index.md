---
title: idx_get()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera element o określonym indeksie. Tylko do odczytu ISummaryZoomSection.
type: docs
weight: 1
url: /pl/aspose.slides/isummaryzoomsectioncollection/idx_get/
---
## ISummaryZoomSectionCollection::idx_get(int32_t) metoda

Pobiera element o określonym indeksie. Tylko do odczytu [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::idx_get(int32_t index)=0
```

## Uwagi

Przykład demonstruje pobieranie elementu Summary Zoom [Section](../../section/) według indeksu: 
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
* Klasa [ISummaryZoomSectionCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)