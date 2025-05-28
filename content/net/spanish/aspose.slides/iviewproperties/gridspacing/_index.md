---
title: EspaciadoDeLaRejilla
second_title: Referencia de la API de Aspose.Slides para .NET
description: Devuelve o establece el espaciado de la rejilla que se debe utilizar para la rejilla subyacente del documento de presentación en puntos. Lectura/escritura Único.
type: docs
weight: 10
url: /es/aspose.slides/iviewproperties/gridspacing/
---

## Propiedad IViewProperties.GridSpacing

Devuelve o establece el espaciado de la rejilla que se debe utilizar para la rejilla subyacente del documento de presentación, en puntos. Lectura/escritura Único.

```csharp
public float GridSpacing { get; set; }
```

### Comentarios

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

### Véase También

* interfaz [IViewProperties](../../iviewproperties)
* espacio de nombres [Aspose.Slides](../../iviewproperties)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->