---
title: set_TargetSlide()
second_title: Aspose.Slides C++ API referenciája
description: Beállítja azt a diaobjektumot, amelyhez a Slide Zoom objektum kapcsolódik. Írja ISlide.
type: docs
weight: 14
url: /hu/aspose.slides/zoomframe/set_targetslide/
---
## ZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) metódus


Beállítja azt a diaobjektumot, amelyhez a [Slide](../../slide/) Zoom objektum kapcsolódik. Írja [ISlide](../../islide/).

```cpp
void Aspose::Slides::ZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value) override
```

## Megjegyzések


A következő példa bemutatja a cél dia módosítását, és új képet hoz létre a [Slide](../../slide/) Zoom objektum számára:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [ISlide](../../islide/)
* Osztály [ZoomFrame](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)