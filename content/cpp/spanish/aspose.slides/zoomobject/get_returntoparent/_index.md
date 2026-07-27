---
title: get_ReturnToParent()
second_title: Referencia de API de Aspose.Slides para C++
description: "Obtiene el comportamiento de navegación en la presentación de diapositivas. Lectura bool. Valor predeterminado: false"
type: docs
weight: 27
url: /es/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() método


Obtiene el comportamiento de navegación en la presentación de diapositivas. Lectura **bool**. Valor predeterminado: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## Observaciones


El valor verdadero de la propiedad especifica el comportamiento de navegación de regreso al elemento padre en la presentación de diapositivas.

Ejemplo: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Ver también

* Clase [ZoomObject](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)