---
title: set_ReturnToParent()
second_title: Referencia de API de Aspose.Slides para C++
description: "Establece el comportamiento de navegación en la presentación de diapositivas. Escriba bool. Valor predeterminado: false"
type: docs
weight: 40
url: /es/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) método

Establece el comportamiento de navegación en la presentación de diapositivas. Escriba **bool**. Valor predeterminado: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## Observaciones

El valor verdadero de la propiedad especifica el comportamiento de navegación de retorno al padre en la presentación de diapositivas. 

Ejemplo: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Ver también

* Clase [ZoomObject](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)