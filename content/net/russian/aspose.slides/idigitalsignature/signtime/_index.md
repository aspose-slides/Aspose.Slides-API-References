---
title: SignTime
second_title: Aspose.Sildes для .NET API Reference
description: Время, когда документ был подписан. Только для чтения DateTime.
type: docs
weight: 40
url: /ru/aspose.slides/idigitalsignature/signtime/
---

## IDigitalSignature.SignTime свойство

Время, когда документ был подписан. Только для чтения DateTime.

```csharp
public DateTime SignTime { get; }
```

### Примеры

```csharp
[C#]
using (Presentation pres = new Presentation("SomePresentationSigned.pptx"))
{
    foreach (DigitalSignature signature in pres.DigitalSignatures)
        Console.WriteLine("Проверка подписи: " + (signature.IsValid ? "ДОПУСТИМА" : "НЕДОПУСТИМА") + ", Время подписи: " + signature.SignTime);
}
```

### См. Также

* interface [IDigitalSignature](../../idigitalsignature)
* namespace [Aspose.Slides](../../idigitalsignature)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->