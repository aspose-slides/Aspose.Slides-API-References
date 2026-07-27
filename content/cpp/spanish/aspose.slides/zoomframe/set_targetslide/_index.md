---
title: set_TargetSlide()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece el objeto diapositiva al que el objeto Slide Zoom enlaza. Escriba ISlide.
type: docs
weight: 14
url: /es/aspose.slides/zoomframe/set_targetslide/
---
## ZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) método

Establece el objeto diapositiva al que el objeto Zoom [Slide](../../slide/) enlaza. Escriba [ISlide](../../islide/).

```cpp
void Aspose::Slides::ZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value) override
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
* Biblioteca [Aspose.Slides](../../../)