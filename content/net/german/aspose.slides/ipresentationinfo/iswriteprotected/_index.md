---
title: IsWriteProtected
second_title: Aspose.Slides für .NET-API-Referenz
description: Ruft einen Wert ab der angibt ob eine gebundene Präsentation schreibgeschützt ist.
type: docs
weight: 30
url: /de/aspose.slides/ipresentationinfo/iswriteprotected/
---
## IPresentationInfo.IsWriteProtected property

Ruft einen Wert ab, der angibt, ob eine gebundene Präsentation schreibgeschützt ist.

```csharp
public NullableBool IsWriteProtected { get; }
```

### Bemerkungen

Wenn die Präsentation zum Öffnen durch ein Kennwort geschützt ist, ist der Eigenschaftswert gleich NotDefined. See[`NullableBool`](../../nullablebool) Aufzählung.

### Beispiele

```csharp
[C#]
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo(presentationFilePath);
if (info.IsWriteProtected == NullableBool.True)
{
    Console.WriteLine("The presentation '" + presentationFilePath + "' is write protected by a password.");
}
```

### Siehe auch

* enum [NullableBool](../../nullablebool)
* interface [IPresentationInfo](../../ipresentationinfo)
* namensraum [Aspose.Slides](../../ipresentationinfo)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
