---
title: IsPasswordProtected
second_title: Référence API Aspose.Slides pour .NET
description: Obtient une valeur qui indique si une présentation liée est protégée par un mot de passe pour s'ouvrir.
type: docs
weight: 20
url: /fr/aspose.slides/ipresentationinfo/ispasswordprotected/
---

## Propriété IPresentationInfo.IsPasswordProtected

Obtient une valeur qui indique si une présentation liée est protégée par un mot de passe pour s'ouvrir.

```csharp
public bool IsPasswordProtected { get; }
```

### Exemples

```csharp
[C#]
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo(presentationFilePath);
if (info.IsPasswordProtected)
{
    Console.WriteLine("La présentation '" + presentationFilePath + "' est protégée par un mot de passe pour s'ouvrir.");
}
```

### Voir aussi

* interface [IPresentationInfo](../../ipresentationinfo)
* namespace [Aspose.Slides](../../ipresentationinfo)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->