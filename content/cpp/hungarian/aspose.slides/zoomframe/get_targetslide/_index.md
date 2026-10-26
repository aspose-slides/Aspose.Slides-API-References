---
title: get_TargetSlide()
second_title: Aspose.Slides for C++ API referencia
description: Visszaadja a diaobjektumot, amelyhez a Slide Zoom objektum kapcsolódik. Olvassa el az ISlide-et.
type: docs
weight: 1
url: /hu/aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() metódus


Megkapja a diaobjektumot, amelyhez a [Slide](../../slide/) Zoom objektum kapcsolódik. Olvasd el [ISlide](../../islide/).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## Megjegyzések


A következő példa bemutatja a céldia módosítását és új kép létrehozását a [Slide](../../slide/) Zoom objektumhoz: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISlide](../../islide/)
* Osztály [ZoomFrame](../)
* Névterület [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)