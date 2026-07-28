---
title: get_Description()
second_title: Referencja API Aspose.Slides dla C++
description: Zwraca tekstowy opis obiektu Summary Zoom Section.
type: docs
weight: 27
url: /pl/aspose.slides/isummaryzoomsection/get_description/
---
## ISummaryZoomSection::get_Description() metoda

Zwraca opis tekstowy obiektu Summary Zoom [Section](../../section/).

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Description()=0
```

## Uwagi

Przykład:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [ISummaryZoomSection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)