---
title: get_ShowBackground()
second_title: Referencia de API de Aspose.Slides para C++
description: "Obtiene el valor que especifica si el Zoom usará el fondo de la diapositiva de destino. Lectura bool. Valor predeterminado: true"
type: docs
weight: 53
url: /es/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() método


Obtiene el valor que especifica si el Zoom usará el fondo de la diapositiva de destino. Lectura **bool**. Valor predeterminado: true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
```

## Observaciones


El ejemplo demuestra cómo eliminar el fondo de una imagen de un objeto Zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Ver también

* Clase [IZoomObject](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)