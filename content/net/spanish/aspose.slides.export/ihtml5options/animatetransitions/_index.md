---
title: AnimateTransitions
second_title: Referencia de la API de Aspose.Slides para .NET
description: Devuelve o establece la opción de animación de transiciones. Lectura/escrituraBoolean .
type: docs
weight: 20
url: /es/aspose.slides.export/ihtml5options/animatetransitions/
---
## IHtml5Options.AnimateTransitions property

Devuelve o establece la opción de animación de transiciones. Lectura/escrituraBoolean .

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

### Ver también

* interface [IHtml5Options](../../ihtml5options)
* espacio de nombres [Aspose.Slides.Export](../../ihtml5options)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
