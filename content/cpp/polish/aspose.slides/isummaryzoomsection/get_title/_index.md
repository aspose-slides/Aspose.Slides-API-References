---
title: get_Title()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zwraca tekstowy tytuł obiektu Summary Zoom Section.
type: docs
weight: 1
url: /pl/aspose.slides/isummaryzoomsection/get_title/
---
## ISummaryZoomSection::get_Title() metoda


Zwraca tekstowy tytuł obiektu Summary Zoom [Section](../../section/).

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Title()=0
```

## Uwagi


Przykład: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [ISummaryZoomSection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)