---
title: set_ReturnToParent()
second_title: Referencia de API de Aspose.Slides para C++
description: "Establece el comportamiento de navegación en la presentación. Escribe bool. Valor predeterminado: false"
type: docs
weight: 40
url: /es/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) método


Establece el comportamiento de navegación en la presentación. Escribe **bool**. Valor predeterminado: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## Observaciones


El valor true de la propiedad especifica el comportamiento de navegación de retorno al padre en la presentación. 

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