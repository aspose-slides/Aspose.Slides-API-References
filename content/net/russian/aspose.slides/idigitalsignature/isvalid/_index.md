---
title: IsValid
second_title: Справочник по API Aspose.Slides для .NET
description: Если эта цифровая подпись действительна и документ не был подделан это значение будет истинным. Только чтениеBoolean.
type: docs
weight: 30
url: /ru/aspose.slides/idigitalsignature/isvalid/
---
## IDigitalSignature.IsValid property

Если эта цифровая подпись действительна и документ не был подделан, это значение будет истинным. Только чтениеBoolean.

```csharp
public bool IsValid { get; }
```

### Примеры

```csharp
[C#]
using (Presentation pres = new Presentation("SomePresentationSigned.pptx"))
{
    foreach (DigitalSignature signature in pres.DigitalSignatures)
        Console.WriteLine("Signature check: " + (signature.IsValid ? "VALID" : "INVALID"));
}
```

### Смотрите также

* interface [IDigitalSignature](../../idigitalsignature)
* пространство имен [Aspose.Slides](../../idigitalsignature)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
