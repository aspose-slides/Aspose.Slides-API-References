---
title: set_ShowBackground()
second_title: Aspose.Slides för C++ API-referens
description: "Ställer in värdet som anger om Zoom ska använda bakgrunden på målsliden. Skriv bool. Standardvärde: true"
type: docs
weight: 66
url: /sv/aspose.slides/izoomobject/set_showbackground/
---
## IZoomObject::set_ShowBackground(bool) metod

Ställer in värdet som anger om Zoom ska använda bakgrunden på målsliden. Skriv **bool**. Standardvärde: true

```cpp
virtual void Aspose::Slides::IZoomObject::set_ShowBackground(bool value)=0
```

## Anmärkningar

Exemplet visar hur man tar bort bakgrunden på en bild av ett Zoom-objekt:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Se också

* Klass [IZoomObject](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)