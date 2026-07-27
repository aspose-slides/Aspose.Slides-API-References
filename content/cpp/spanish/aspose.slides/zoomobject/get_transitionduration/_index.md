---
title: get_TransitionDuration()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Obtiene la duración de la transición entre Zoom y diapositiva. Tipo float. Valor predeterminado: 1.0f"
type: docs
weight: 105
url: /es/aspose.slides/zoomobject/get_transitionduration/
---
## ZoomObject::get_TransitionDuration() método

Obtiene la duración de la transición entre Zoom y diapositiva. Tipo **float**. Valor predeterminado: 1.0f

```cpp
float Aspose::Slides::ZoomObject::get_TransitionDuration() override
```

## Observaciones

Si no se especifica (TransitionDur = 0), se utilizará la transición de la diapositiva de destino y los tiempos asociados a esa transición. 

El ejemplo muestra cómo cambiar la duración de la transición entre Zoom y diapositiva: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Ver también

* Clase [ZoomObject](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)