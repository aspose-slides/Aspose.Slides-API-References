---
title: IsValid
second_title: Referencia de la API de Aspose.Slides para .NET
description: Si esta firma digital es válida y el documento no ha sido alterado, este valor será verdadero. Booleano de solo lectura.
type: docs
weight: 30
url: /es/aspose.slides/idigitalsignature/isvalid/
---

## Propiedad IDigitalSignature.IsValid

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
        Console.WriteLine("Verificación de firma: " + (signature.IsValid ? "VÁLIDA" : "INVALIDA"));
}
```

### Véase también

* interfaz [IDigitalSignature](../../idigitalsignature)
* espacio de nombres [Aspose.Slides](../../idigitalsignature)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->