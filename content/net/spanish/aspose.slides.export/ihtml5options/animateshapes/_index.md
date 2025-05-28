---
title: AnimateShapes
second_title: Referencia de la API de Aspose.Slides para .NET
description: Devuelve o establece la opción de animación de formas. Booleano de lectura/escritura.
type: docs
weight: 10
url: /es/aspose.slides.export/ihtml5options/animateshapes/
---

## Propiedad IHtml5Options.AnimateShapes

Devuelve o establece la opción de animación de formas. Booleano de lectura/escritura.

```csharp
public bool AnimateShapes { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
  pres.Save("demo-animate-shapes.html", SaveFormat.Html5, new Html5Options()
  {
      AnimateShapes = true
  });
}
```

### Véase También

* interfaz [IHtml5Options](../../ihtml5options)
* espacio de nombres [Aspose.Slides.Export](../../ihtml5options)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->
