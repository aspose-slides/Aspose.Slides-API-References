---
title: CheckWriteProtection
second_title: Aspose.Sildes for .NET API Reference
description: Bestimmt, ob eine Präsentation passwortgeschützt ist, um sie zu bearbeiten.
type: docs
weight: 70
url: /de/aspose.slides/protectionmanager/checkwriteprotection/
---

## ProtectionManager.CheckWriteProtection Methode

Bestimmt, ob eine Präsentation passwortgeschützt ist, um sie zu bearbeiten.

```csharp
public bool CheckWriteProtection(string password)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| password | String | Das Passwort für die Überprüfung. |

### Rückgabewert

True, wenn das Passwort gültig ist; andernfalls false.

### Bemerkungen

1. Sie sollten die [`IsWriteProtected`](../iswriteprotected) Eigenschaft überprüfen, bevor Sie diese Methode aufrufen. 2. Wenn das Passwort null oder leer ist, gibt diese Methode false zurück.

### Beispiele

```csharp
[C#]
using (var presentation = new Presentation(presentationFilePath))
{
    var isWriteProtected = presentation.ProtectionManager.CheckWriteProtection("my_password");
}
```

### Siehe Auch

* Klasse [ProtectionManager](../../protectionmanager)
* Namespace [Aspose.Slides](../../protectionmanager)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->