---
title: SetWriteProtection
second_title: Aspose.Slides pour référence API .NET
description: Définir la protection en écriture pour cette présentation avec un mot de passe spécifié.
type: docs
weight: 110
url: /fr/aspose.slides/protectionmanager/setwriteprotection/
---

## ProtectionManager.SetWriteProtection méthode

Définir la protection en écriture pour cette présentation avec un mot de passe spécifié.

```csharp
public void SetWriteProtection(string password)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| password | String | Le mot de passe. |

### Exemples

Le code d'exemple suivant vous montre comment définir une protection en écriture pour une présentation.

```csharp
[C#]
using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.SetWriteProtection("123123");
    presentation.Save("write-protected-pres.pptx", SaveFormat.Pptx);
}
```

### Voir aussi

* class [ProtectionManager](../../protectionmanager)
* namespace [Aspose.Slides](../../protectionmanager)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->