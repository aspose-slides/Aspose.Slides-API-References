---
title: IsValid
second_title: Referencia de la API Aspose.Slides para .NET
description: Si esta firma digital es válida y el documento no ha sido manipulado, este valor será true. Solo lectura Boolean.
type: docs
weight: 30
url: /es/aspose.slides/idigitalsignature/isvalid/
---

## Propiedad IDigitalSignature.IsValid

Si esta firma digital es válida y el documento no ha sido manipulado, este valor será true. Solo lectura Boolean.

```csharp
public bool IsValid { get; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation("SomePresentationSigned.pptx"))
{
    foreach (DigitalSignature signature in pres.DigitalSignatures)
        Console.WriteLine("Verificación de la firma: " + (signature.IsValid ? "VÁLIDA" : "INVÁLIDA"));
}
```

### Véase también

* interfaz [IDigitalSignature](../../idigitalsignature)
* espacio de nombres [Aspose.Slides](../../idigitalsignature)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->