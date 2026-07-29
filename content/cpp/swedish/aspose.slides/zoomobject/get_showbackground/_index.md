---
title: get_ShowBackground()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar värdet som anger om Zoom kommer att använda bakgrunden på destinationssliden. Läs bool. Standardvärde: true"
type: docs
weight: 53
url: /sv/aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() metod


Hämtar värdet som anger om Zoom kommer att använda bakgrunden på destinationssliden. Läs **bool**. Standardvärde: true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
```

## Anmärkningar


exemplet demonstrerar borttagning av bakgrunden på en bild av ett Zoom-objekt: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Se även

* Klass [ZoomObject](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)