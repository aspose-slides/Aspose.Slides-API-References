---
title: Delimit
second_title: Aspose.Slides pour .NET API Référence
description: Délimite les arguments en utilisant le caractère de délimitation spécifié
type: docs
weight: 80
url: /fr/aspose.slides.mathtext/imathdelimiter/delimit/
---

## IMathDelimiter.Delimit méthode

Délimite les arguments en utilisant le caractère de délimitation spécifié

```csharp
public IMathDelimiter Delimit(char separatorCharacter)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| separatorCharacter | Char | caractère de délimitation |

### Valeur de retour

Cet objet après l'application du caractère de délimitation

### Exemples

Exemple:

```csharp
[C#]
IMathDelimiter delimiter = new MathematicalText("x").Join("y").Enclose();
delimiter.Delimit('|');
```

### Voir aussi

* interface [IMathDelimiter](../../imathdelimiter)
* namespace [Aspose.Slides.MathText](../../imathdelimiter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->