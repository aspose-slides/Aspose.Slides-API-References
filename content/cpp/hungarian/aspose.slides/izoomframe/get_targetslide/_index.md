---
title: get_TargetSlide()
second_title: Aspose.Slides for C++ API referencia
description: Lekéri a dia objektumot, amelyhez a Slide Zoom objektum kapcsolódik. Olvassa el ISlide.
type: docs
weight: 1
url: /hu/aspose.slides/izoomframe/get_targetslide/
---
## IZoomFrame::get_TargetSlide() metódus

Lekéri a dia objektumot, amelyhez a [Slide](../../slide/) Zoom objektum kapcsolódik. Olvassa el [ISlide](../../islide/).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::IZoomFrame::get_TargetSlide()=0
```

## Megjegyzés

A következő példa bemutatja a cél dia módosítását, és új képet hoz létre a [Slide](../../slide/) Zoom objektumhoz:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISlide](../../islide/)
* Osztály [IZoomFrame](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)