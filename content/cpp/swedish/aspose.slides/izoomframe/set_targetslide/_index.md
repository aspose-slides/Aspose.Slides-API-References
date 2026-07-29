---
title: set_TargetSlide()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in slide-objektet som Slide Zoom-objektet länkar till. Skriv ISlide.
type: docs
weight: 14
url: /sv/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) metod

Ställer in slide-objektet som [Slide](../../slide/) Zoom-objekt länkar till. Skriv [ISlide](../../islide/).

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
```

## Anmärkningar

Nästa exempel demonstrerar hur man ändrar mål-slide och skapar en ny bild för [Slide](../../slide/) Zoom-objektet:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [ISlide](../../islide/)
* Klass [IZoomFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)