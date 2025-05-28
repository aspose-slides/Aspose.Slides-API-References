---
title: OutputPath
second_title: Referencia de la API de Aspose.Slides para .NET
description: Determina dónde deben almacenarse los recursos externos. Cadena de lectura/escritura.
type: docs
weight: 60
url: /es/aspose.slides.export/html5options/outputpath/
---

## Propiedad Html5Options.OutputPath

Determina dónde deben almacenarse los recursos externos. Cadena de lectura/escritura.

```csharp
public string OutputPath { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
  pres.Save("demo-linked-images.html", SaveFormat.Html5, new Html5Options()
  {
      EmbedImages = true,
      OutputPath = "the_desired_path"
  });
}
```

### Vea También

* clase [Html5Options](../../html5options)
* espacio de nombres [Aspose.Slides.Export](../../html5options)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->