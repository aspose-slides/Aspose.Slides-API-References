---
title: EmbedImages
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve o establece la opción de incrustar imágenes. Booleano de lectura/escritura.
type: docs
weight: 50
url: /es/aspose.slides.export/ihtml5options/embedimages/
---

## IHtml5Options.EmbedImages property

Devuelve o establece la opción de incrustar imágenes. Booleano de lectura/escritura.

```csharp
public bool EmbedImages { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
  pres.Save("demo-linked-images.html", SaveFormat.Html5, new Html5Options()
  {
      EmbedImages = false
  });
}
```

### Vea También

* interfaz [IHtml5Options](../../ihtml5options)
* espacio de nombres [Aspose.Slides.Export](../../ihtml5options)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->