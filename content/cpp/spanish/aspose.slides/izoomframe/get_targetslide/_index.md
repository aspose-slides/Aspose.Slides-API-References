---
title: get_TargetSlide()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene el objeto diapositiva al que el objeto Slide Zoom enlaza. Lea ISlide.
type: docs
weight: 1
url: /es/aspose.slides/izoomframe/get_targetslide/
---
## IZoomFrame::get_TargetSlide() método

Obtiene el objeto diapositiva al que el objeto Zoom [Slide](../../slide/) enlaza. Lea [ISlide](../../islide/).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::IZoomFrame::get_TargetSlide()=0
```
## Observaciones

El siguiente ejemplo muestra cómo cambiar la diapositiva objetivo y crea una nueva imagen para el objeto Zoom [Slide](../../slide/):
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISlide](../../islide/)
* Clase [IZoomFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)