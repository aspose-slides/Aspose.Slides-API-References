---
title: set_TargetSlide()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Nastavuje objekt snímku, na který odkazuje objekt Slide Zoom. Zapište ISlide.
type: docs
weight: 14
url: /cs/aspose.slides/zoomframe/set_targetslide/
---
## ZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) metoda

Nastavuje objekt snímku, na který odkazuje objekt [Slide](../../slide/) Zoom. Zapište [ISlide](../../islide/).

```cpp
void Aspose::Slides::ZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value) override
```

## Poznámky

Další příklad ukazuje změnu cílového snímku a vytváří nový obrázek pro objekt [Slide](../../slide/) Zoom:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISlide](../../islide/)
* Třída [ZoomFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)