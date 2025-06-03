---
title: GridSpacing
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve o establece el espaciado de la rejilla que se debe utilizar para la rejilla subyacente del documento de presentación en puntos. Lectura/escritura Single.
type: docs
weight: 10
url: /es/aspose.slides/viewproperties/gridspacing/
---

## Propiedad ViewProperties.GridSpacing

Devuelve o establece el espaciado de la rejilla que se debe utilizar para la rejilla subyacente del documento de presentación, en puntos. Lectura/escritura Single.

```csharp
public float GridSpacing { get; set; }
```

### Observaciones

El valor del espaciado de la rejilla debe ser un número positivo. El rango de valores típico es de 1 mm (2.8349607 puntos) a 2 pulgadas (144 puntos).

### Ejemplos

El siguiente código de muestra muestra cómo cambiar el espaciado de la rejilla en una presentación de PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    pres.ViewProperties.GridSpacing = 72f;
    pres.Save("GridSpacing_out.pptx", SaveFormat.Pptx);
}
```

### Véase también

* clase [ViewProperties](../../viewproperties)
* espacio de nombres [Aspose.Slides](../../viewproperties)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->