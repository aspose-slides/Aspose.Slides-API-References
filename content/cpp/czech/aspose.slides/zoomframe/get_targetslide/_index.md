---
title: get_TargetSlide()
second_title: Aspose.Slides pro C++ API Reference
description: Získá objekt snímku, na který odkazuje objekt Slide Zoom. Přečtěte si ISlide.
type: docs
weight: 1
url: /cs/aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() metoda


Získá objekt snímku, na který odkazuje objekt [Slide](../../slide/) Zoom. Přečtěte si [ISlide](../../islide/).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## Poznámky


Další příklad ukazuje změnu cílového snímku a vytváří nový obrázek pro objekt [Slide](../../slide/) Zoom: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [ISlide](../../islide/)
* třída [ZoomFrame](../)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)