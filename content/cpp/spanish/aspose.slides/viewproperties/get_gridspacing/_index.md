---
title: get_GridSpacing()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el espaciado de la cuadrícula que debe usarse para la cuadrícula subyacente al documento de presentación, en puntos. Lea float.
type: docs
weight: 92
url: /es/aspose.slides/viewproperties/get_gridspacing/
---
## ViewProperties::get_GridSpacing() método


Devuelve el espaciado de la cuadrícula que debe usarse para la cuadrícula subyacente al documento de presentación, en puntos. Lea **float**.

```cpp
float Aspose::Slides::ViewProperties::get_GridSpacing() override
```

## Observaciones


El valor del espaciado de la cuadrícula debe ser un número positivo. El rango típico de valores es de 1 mm (2.8349607 puntos) a 2 pulgadas (144 puntos). 

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