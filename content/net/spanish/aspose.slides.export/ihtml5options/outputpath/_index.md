---
title: OutputPath
second_title: Aspose.Sildes para .NET Referencia de API
description: Determina dónde deben ser almacenados los recursos externos. Lectura/escritura String.
type: docs
weight: 60
url: /es/aspose.slides.export/ihtml5options/outputpath/
---

## Propiedad IHtml5Options.OutputPath

Determina dónde deben ser almacenados los recursos externos. Lectura/escritura String.

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
      EmbedImages = false,
      OutputPath = "the_desired_path"
  });
}
```

### Ver También

* interfaz [IHtml5Options](../../ihtml5options)
* espacio de nombres [Aspose.Slides.Export](../../ihtml5options)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->