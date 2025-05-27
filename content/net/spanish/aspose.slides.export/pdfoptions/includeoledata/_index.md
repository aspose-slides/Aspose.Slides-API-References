---
title: IncludeOleData
second_title: Referencia de la API de Aspose.Slides para .NET
description: Verdadero para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Lectura/escritura Booleano.
type: docs
weight: 110
url: /es/aspose.slides.export/pdfoptions/includeoledata/
---

## PdfOptions.IncludeOleData propiedad

Verdadero para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Lectura/escritura Booleano.

```csharp
public bool IncludeOleData { get; set; }
```

### Observaciones

El valor predeterminado es **false**.

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    PdfOptions options = new PdfOptions { IncludeOleData = true };
    pres.Save("pres.pdf", SaveFormat.Pdf, options);
}
```

### Véase también

* clase [PdfOptions](../../pdfoptions)
* espacio de nombres [Aspose.Slides.Export](../../pdfoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->