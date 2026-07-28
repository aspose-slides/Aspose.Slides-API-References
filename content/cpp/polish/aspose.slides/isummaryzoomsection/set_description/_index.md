---
title: set_Description()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca tekstowy opis obiektu Summary Zoom Section.
type: docs
weight: 40
url: /pl/aspose.slides/isummaryzoomsection/set_description/
---
## ISummaryZoomSection::set_Description(System::String) metoda


Zwraca tekstowy opis obiektu Summary Zoom [Section](../../section/).

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Description(System::String value)=0
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