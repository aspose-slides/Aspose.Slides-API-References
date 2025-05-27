---
title: EmbedImages
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve o establece la opción de incrustación de imágenes. Booleano de lectura/escritura.
type: docs
weight: 50
url: /es/aspose.slides.export/ihtml5options/embedimages/
---

## Propiedad IHtml5Options.EmbedImages

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

### Véase también

* interfaz [IHtml5Options](../../ihtml5options)
* espacio de nombres [Aspose.Slides.Export](../../ihtml5options)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->