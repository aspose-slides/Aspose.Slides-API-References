---
title: Zip64Mode
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica si se utiliza el formato ZIP64 para el documento de Presentación. El valor predeterminado es IfNecessary
type: docs
weight: 40
url: /es/aspose.slides.export/ipptxoptions/zip64mode/
---

## Propiedad IPptxOptions.Zip64Mode

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

### Véase también

* enum [Zip64Mode](../../zip64mode)
* interface [IPptxOptions](../../ipptxoptions)
* namespace [Aspose.Slides.Export](../../ipptxoptions)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->