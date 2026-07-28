---
title: get_Title()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca tytuł tekstowy obiektu Summary Zoom Section.
type: docs
weight: 1
url: /pl/aspose.slides/summaryzoomsection/get_title/
---
## SummaryZoomSection::get_Title() metoda


Zwraca tytuł tekstowy obiektu Summary Zoom [Section](../../section/).

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Title() override
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