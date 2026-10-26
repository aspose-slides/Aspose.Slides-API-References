---
title: set_TransitionDuration()
second_title: Referencia de API de Aspose.Slides para C++
description: "Establece la duración de la transición entre Zoom y diapositiva. Escriba float. Valor predeterminado: 1.0f"
type: docs
weight: 118
url: /es/aspose.slides/izoomobject/set_transitionduration/
---
## IZoomObject::set_TransitionDuration(float) método


Establece la duración de la transición entre Zoom y diapositiva. Escriba **float**. Valor predeterminado: 1.0f

```cpp
virtual void Aspose::Slides::IZoomObject::set_TransitionDuration(float value)=0
```

## Observaciones


Si no se especifica (TransitionDur = 0), se utilizará la transición de diapositiva de destino y los tiempos asociados con esa transición. 

El ejemplo demuestra cómo cambiar la duración de la transición entre Zoom y diapositiva: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Véase también

* Clase [IZoomObject](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)