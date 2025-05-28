---
title: AnimateTransitions
second_title: Referencia de la API de Aspose.Slides para .NET
description: Establece o devuelve la opción de animación de transiciones. Booleano de lectura/escritura.
type: docs
weight: 20
url: /es/aspose.slides.export/ihtml5options/animatetransitions/
---

## Propiedad IHtml5Options.AnimateTransitions

Establece o devuelve la opción de animación de transiciones. Booleano de lectura/escritura.

```csharp
public bool AnimateTransitions { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
  pres.Save("demo-animate-transitions.html", SaveFormat.Html5, new Html5Options()
  {
      AnimateTransitions = true
  });
}
```

### Ver También

* interfaz [IHtml5Options](../../ihtml5options)
* espacio de nombres [Aspose.Slides.Export](../../ihtml5options)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->