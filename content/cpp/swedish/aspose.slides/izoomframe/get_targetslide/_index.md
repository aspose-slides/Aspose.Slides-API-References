---
title: get_TargetSlide()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar bildobjektet som Slide Zoom-objektet länkar till. Läs ISlide.
type: docs
weight: 1
url: /sv/aspose.slides/izoomframe/get_targetslide/
---
## IZoomFrame::get_TargetSlide() metod

Hämtar bildobjektet som [Slide](../../slide/) Zoom-objektet länkar till. Läs [ISlide](../../islide/).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::IZoomFrame::get_TargetSlide()=0
```

## Anmärkningar

Nästa exempel visar hur man ändrar målbilden och skapar en ny bild för [Slide](../../slide/) Zoom-objektet:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISlide](../../islide/)
* Klass [IZoomFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)