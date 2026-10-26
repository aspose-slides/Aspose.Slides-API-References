---
title: set_GridSpacing()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece el espaciado de la cuadrícula que debe usarse para la cuadrícula subyacente al documento de presentación, en puntos. Escriba float.
type: docs
weight: 105
url: /es/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) método

Establece el espaciado de la cuadrícula que debe usarse para la cuadrícula subyacente al documento de presentación, en puntos. Escriba **float**.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
```

## Observaciones

El valor del espaciado de la cuadrícula debe ser un número positivo. El rango típico es de 1 mm (2.8349607 puntos) a 2 pulgadas (144 puntos). 

El siguiente código de ejemplo muestra cómo cambiar el espaciado de la cuadrícula en una presentación de PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Ver también

* Clase [ViewProperties](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)