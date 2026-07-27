---
title: get_ReturnToParent()
second_title: Referencia de API de Aspose.Slides para C++
description: "Obtiene el comportamiento de navegación en la presentación de diapositivas. Lectura **bool**. Valor predeterminado: false"
type: docs
weight: 27
url: /es/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() método


Obtiene el comportamiento de navegación en la presentación de diapositivas. Lectura **bool**. Valor predeterminado: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## Observaciones


El valor verdadero de la propiedad indica el comportamiento de navegación de regreso al elemento padre en la presentación de diapositivas. 

Ejemplo: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Ver también

* Clase [IZoomObject](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)