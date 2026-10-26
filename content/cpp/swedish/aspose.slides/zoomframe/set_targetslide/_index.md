---
title: set_TargetSlide()
second_title: Aspose.Slides för C++ API-referens
description: Anger bildobjektet som Slide Zoom-objektet länkar till. Skriv ISlide.
type: docs
weight: 14
url: /sv/aspose.slides/zoomframe/set_targetslide/
---
## ZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) metod

Anger bildobjektet som [Slide](../../slide/) Zoom-objektet länkar till. Skriv [ISlide](../../islide/).

```cpp
void Aspose::Slides::ZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value) override
```

## Anmärkningar

Nästa exempel demonstrerar ändring av målbilden och skapar en ny bild för [Slide](../../slide/) Zoom-objektet:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISlide](../../islide/)
* Klass [ZoomFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)