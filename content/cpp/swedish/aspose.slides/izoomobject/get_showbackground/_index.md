---
title: get_ShowBackground()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar värdet som anger om Zoom ska använda bakgrunden på destinationsbilden. Läser bool. Standardvärde: true"
type: docs
weight: 53
url: /sv/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() metod

Hämtar värdet som anger om Zoom ska använda bakgrunden på destinationsbilden. Läser **bool**. Standardvärde: true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
```

## Anmärkningar

Exemplet visar hur man tar bort bakgrunden på en bild av ett Zoom-objekt:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Se även

* Klass [IZoomObject](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)