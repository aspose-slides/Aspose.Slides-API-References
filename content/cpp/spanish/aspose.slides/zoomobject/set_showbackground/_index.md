---
title: set_ShowBackground()
second_title: Aspose.Slides para la referencia de la API de C++
description: "Establece el valor que especifica si el Zoom usará el fondo de la diapositiva de destino. Escribe bool. Valor predeterminado: true"
type: docs
weight: 66
url: /es/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) método


Establece el valor que especifica si el Zoom usará el fondo de la diapositiva de destino. Escribe **bool**. Valor predeterminado: true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
```

## Observaciones


El ejemplo muestra cómo eliminar el fondo de una imagen de un objeto Zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Ver también

* Clase [ZoomObject](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)