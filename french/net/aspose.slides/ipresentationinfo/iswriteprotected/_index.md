---
title: IsWriteProtected
second_title: Référence de l'API Aspose.Slides pour .NET
description: Obtient une valeur qui indique si une présentation liée est protégée en écriture.
type: docs
weight: 30
url: /fr/net/aspose.slides/ipresentationinfo/iswriteprotected/
---
## IPresentationInfo.IsWriteProtected property

Obtient une valeur qui indique si une présentation liée est protégée en écriture.

```csharp
public NullableBool IsWriteProtected { get; }
```

### Remarques

Si la présentation est protégée par un mot de passe pour s'ouvrir, la valeur de la propriété vaut NotDefined. Voir[`NullableBool`](../../nullablebool) énumération.

### Exemples

```csharp
[C#]
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo(presentationFilePath);
if (info.IsWriteProtected == NullableBool.True)
{
    Console.WriteLine("The presentation '" + presentationFilePath + "' is write protected by a password.");
}
```

### Voir également

* enum [NullableBool](../../nullablebool)
* interface [IPresentationInfo](../../ipresentationinfo)
* espace de noms [Aspose.Slides](../../ipresentationinfo)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->