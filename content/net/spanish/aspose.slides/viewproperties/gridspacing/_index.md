---
title: GridSpacing
second_title: Aspose.Sildes para .NET Referencia de API
description: Devuelve o establece el espaciado de la cuadrícula que debe usarse para la cuadrícula subyacente del documento de presentación en puntos. Lectura/escritura Simple.
type: docs
weight: 10
url: /es/aspose.slides/viewproperties/gridspacing/
---

## ViewProperties.GridSpacing propiedad

Devuelve o establece el espaciado de la cuadrícula que debe usarse para la cuadrícula subyacente del documento de presentación, en puntos. Lectura/escritura Simple.

```csharp
public float GridSpacing { get; set; }
```

### Observaciones

El valor del espaciado de la cuadrícula debe ser un número positivo. El rango típico de valores es de 1 mm (2.8349607 puntos) a 2 pulgadas (144 puntos).

### Ejemplos

El siguiente código de ejemplo muestra cómo cambiar el espaciado de la cuadrícula en una presentación de PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    pres.ViewProperties.GridSpacing = 72f;
    pres.Save("GridSpacing_out.pptx", SaveFormat.Pptx);
}
```

### Ver También

* clase [ViewProperties](../../viewproperties)
* espacio de nombres [Aspose.Slides](../../viewproperties)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->