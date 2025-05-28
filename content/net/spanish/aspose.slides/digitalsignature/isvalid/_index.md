---
title: IsValid
second_title: Referencia de la API de Aspose.Slides para .NET
description: Si esta firma digital es válida y el documento no ha sido manipulado, este valor será verdadero. Solo lectura Booleano.
type: docs
weight: 40
url: /es/aspose.slides/digitalsignature/isvalid/
---

## Propiedad DigitalSignature.IsValid

Si esta firma digital es válida y el documento no ha sido manipulado, este valor será verdadero. Solo lectura Booleano.

```csharp
public bool IsValid { get; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation("SomePresentationSigned.pptx"))
{
    foreach (DigitalSignature signature in pres.DigitalSignatures)
        Console.WriteLine("Verificación de firma: " + (signature.IsValid ? "VÁLIDO" : "NO VÁLIDO"));
}
```

### Véase también

* clase [DigitalSignature](../../digitalsignature)
* espacio de nombres [Aspose.Slides](../../digitalsignature)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->