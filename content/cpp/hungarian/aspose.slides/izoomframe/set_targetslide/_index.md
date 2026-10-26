---
title: set_TargetSlide()
second_title: Aspose.Slides C++ API hivatkozás
description: Beállítja azt a diát, amelyhez a Slide Zoom objektum kapcsolódik. Írja ISlide.
type: docs
weight: 14
url: /hu/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) metódus


Beállítja azt a diát, amelyhez a [Slide](../../slide/) Zoom objektum kapcsolódik. Írja [ISlide](../../islide/).

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
```

## Megjegyzések


A következő példa bemutatja a cél-dia módosítását és új képet hoz létre a [Slide](../../slide/) Zoom objektum számára: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISlide](../../islide/)
* Osztály [IZoomFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)