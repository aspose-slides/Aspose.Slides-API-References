---
title: IncludeOleData
second_title: Referencia de API de Aspose.Slides para .NET
description: Verdadero para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Lectura/escritura Booleano.
type: docs
weight: 110
url: /es/aspose.slides.export/ipdfoptions/includeoledata/
---

## Propiedad IPdfOptions.IncludeOleData

Verdadero para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Lectura/escritura Booleano.

```csharp
public bool IncludeOleData { get; set; }
```

### Comentarios

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

* interfaz [IPdfOptions](../../ipdfoptions)
* espacio de nombres [Aspose.Slides.Export](../../ipdfoptions)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->