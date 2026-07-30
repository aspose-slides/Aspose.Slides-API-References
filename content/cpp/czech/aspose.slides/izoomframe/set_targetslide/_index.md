---
title: set_TargetSlide()
second_title: Aspose.Slides pro referenci API C++
description: Nastaví objekt snímku, na který odkazuje objekt Slide Zoom. Zapište ISlide.
type: docs
weight: 14
url: /cs/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) metoda

Nastaví objekt snímku, na který odkazuje objekt [Slide](../../slide/) Zoom. Zapište [ISlide](../../islide/).

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
```

## Poznámky

Následující příklad ukazuje změnu cílového snímku a vytváří nový obrázek pro objekt [Slide](../../slide/) Zoom:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [ISlide](../../islide/)
* třída [IZoomFrame](../)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)