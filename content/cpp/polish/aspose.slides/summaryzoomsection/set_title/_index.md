---
title: set_Title()
second_title: Odwołanie API Aspose.Slides dla C++
description: Zwraca tekstowy tytuł obiektu Summary Zoom Section.
type: docs
weight: 14
url: /pl/aspose.slides/summaryzoomsection/set_title/
---
## SummaryZoomSection::set_Title(System::String) metoda


Zwraca tekstowy tytuł obiektu Summary Zoom [Section](../../section/).

```cpp
void Aspose::Slides::SummaryZoomSection::set_Title(System::String value) override
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
* Klasa [SummaryZoomSection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)