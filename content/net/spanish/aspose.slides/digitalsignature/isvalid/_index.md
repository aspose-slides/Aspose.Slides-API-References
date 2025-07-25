---
title: IsValid
second_title: Referencia de la API Aspose.Slides para .NET
description: Si esta firma digital es válida y el documento no ha sido alterado, este valor será verdadero. Booleano de solo lectura.
type: docs
weight: 40
url: /es/aspose.slides/digitalsignature/isvalid/
---

## Propiedad DigitalSignature.IsValid

Si esta firma digital es válida y el documento no ha sido alterado, este valor será verdadero. Booleano de solo lectura.

```csharp
public bool IsValid { get; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation("SomePresentationSigned.pptx"))
{
    foreach (DigitalSignature signature in pres.DigitalSignatures)
        Console.WriteLine("Verificación de firma: " + (signature.IsValid ? "VÁLIDO" : "INVÁLIDO"));
}
```

### Véase también

* clase [DigitalSignature](../../digitalsignature)
* espacio de nombres [Aspose.Slides](../../digitalsignature)
* ensamblado [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->