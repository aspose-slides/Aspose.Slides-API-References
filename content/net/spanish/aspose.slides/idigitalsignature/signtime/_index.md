---
title: SignTime
second_title: Referencia de la API de Aspose.Slides para .NET
description: El momento en que se firmó el documento. Solo lectura DateTime.
type: docs
weight: 40
url: /es/aspose.slides/idigitalsignature/signtime/
---

## Propiedad IDigitalSignature.SignTime

El momento en que se firmó el documento. Solo lectura DateTime.

```csharp
public DateTime SignTime { get; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation("SomePresentationSigned.pptx"))
{
    foreach (DigitalSignature signature in pres.DigitalSignatures)
        Console.WriteLine("Verificación de firma: " + (signature.IsValid ? "VÁLIDA" : "INVALIDA") + ", Hora de firma: " + signature.SignTime);
}
```

### Véase También

* interfaz [IDigitalSignature](../../idigitalsignature)
* espacio de nombres [Aspose.Slides](../../idigitalsignature)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->