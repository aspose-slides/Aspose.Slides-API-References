---
title: get_TargetSlide()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el objeto diapositiva al que enlaza el objeto Slide Zoom. Lea ISlide.
type: docs
weight: 1
url: /es/aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() método

Obtiene el objeto diapositiva al que el objeto Zoom [Slide](../../slide/) enlaza. Lea [ISlide](../../islide/).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## Observaciones

El siguiente ejemplo demuestra cómo cambiar la diapositiva de destino y crea una nueva imagen para el objeto Zoom [Slide](../../slide/):

```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISlide](../../islide/)
* Clase [ZoomFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)