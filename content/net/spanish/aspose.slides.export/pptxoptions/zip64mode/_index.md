---
title: Zip64Mode
second_title: Referencia de la API de Aspose.Slides para .NET
description: Especifica si se utiliza el formato ZIP64 para el documento de Presentación. El valor predeterminado es IfNecessary
type: docs
weight: 40
url: /es/aspose.slides.export/pptxoptions/zip64mode/
---

## PptxOptions.Zip64Mode propiedad

Especifica si se utiliza el formato ZIP64 para el documento de Presentación. El valor predeterminado es IfNecessary

```csharp
public Zip64Mode Zip64Mode { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
    pres.Save("demo-zip64.pptx", SaveFormat.Pptx, new PptxOptions()
    {
        Zip64Mode = Zip64Mode.Always
    });
}
```

### Ver También

* enum [Zip64Mode](../../zip64mode)
* class [PptxOptions](../../pptxoptions)
* namespace [Aspose.Slides.Export](../../pptxoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
