---
title: get_TargetSlide()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar slide-objektet som Slide Zoom-objektet länkar till. Läs ISlide.
type: docs
weight: 1
url: /sv/aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() metod

Hämtar slide-objektet som [Slide](../../slide/) Zoom-objekt länkar till. Läs [ISlide](../../islide/).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## Anmärkningar

Nästa exempel visar hur man ändrar mål-sliden och skapar en ny bild för [Slide](../../slide/) Zoom-objektet:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISlide](../../islide/)
* Klass [ZoomFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)