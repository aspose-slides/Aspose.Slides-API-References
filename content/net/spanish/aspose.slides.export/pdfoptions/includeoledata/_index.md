---
title: IncludeOleData
second_title: Aspose.Sildes para .NET Referencia de API
description: Verdadero para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Booleano de lectura/escritura.
type: docs
weight: 110
url: /es/aspose.slides.export/pdfoptions/includeoledata/
---

## PdfOptions.IncludeOleData propiedad

Verdadero para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Booleano de lectura/escritura.

```csharp
public bool IncludeOleData { get; set; }
```

### Observaciones

El valor predeterminado es **falso**.

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

### Ver También

* clase [PdfOptions](../../pdfoptions)
* espacio de nombres [Aspose.Slides.Export](../../pdfoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->