---
title: SignTime
second_title: Referencia de la API de Aspose.Slides para .NET
description: La hora en que se firmó el documento. Solo lecturaDateTime .
type: docs
weight: 50
url: /es/aspose.slides/digitalsignature/signtime/
---
## DigitalSignature.SignTime property

La hora en que se firmó el documento. Solo lecturaDateTime .

```csharp
public DateTime SignTime { get; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation("SomePresentationSigned.pptx"))
{
    foreach (DigitalSignature signature in pres.DigitalSignatures)
        Console.WriteLine("Signature check: " + (signature.IsValid ? "VALID" : "INVALID") + ", Signing time: " + signature.SignTime);
}
```

### Ver también

* class [DigitalSignature](../../digitalsignature)
* espacio de nombres [Aspose.Slides](../../digitalsignature)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
