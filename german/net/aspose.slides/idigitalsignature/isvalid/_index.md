---
title: IsValid
second_title: Aspose.Slides für .NET-API-Referenz
description: Wenn diese digitale Signatur gültig ist und das Dokument nicht manipuliert wurde ist dieser Wert wahr. SchreibgeschütztBoolean .
type: docs
weight: 30
url: /de/net/aspose.slides/idigitalsignature/isvalid/
---
## IDigitalSignature.IsValid property

Wenn diese digitale Signatur gültig ist und das Dokument nicht manipuliert wurde, ist dieser Wert wahr. SchreibgeschütztBoolean .

```csharp
public bool IsValid { get; }
```

### Beispiele

```csharp
[C#]
using (Presentation pres = new Presentation("SomePresentationSigned.pptx"))
{
    foreach (DigitalSignature signature in pres.DigitalSignatures)
        Console.WriteLine("Signature check: " + (signature.IsValid ? "VALID" : "INVALID"));
}
```

### Siehe auch

* interface [IDigitalSignature](../../idigitalsignature)
* namensraum [Aspose.Slides](../../idigitalsignature)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->