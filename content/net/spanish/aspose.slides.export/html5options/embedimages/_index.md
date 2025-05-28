---
title: EmbedImages
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve o establece la opción de incrustación de imágenes. Booleano de lectura/escritura.
type: docs
weight: 50
url: /es/aspose.slides.export/html5options/embedimages/
---

## Propiedad Html5Options.EmbedImages

Devuelve o establece la opción de incrustación de imágenes. Booleano de lectura/escritura.

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

### Véase También

* class [Html5Options](../../html5options)
* namespace [Aspose.Slides.Export](../../html5options)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->