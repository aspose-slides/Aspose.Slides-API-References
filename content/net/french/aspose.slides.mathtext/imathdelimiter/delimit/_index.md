---
title: Delimit
second_title: Référence de l'API Aspose.Slides pour .NET
description: Délimite les arguments à laide du caractère délimiteur spécifié
type: docs
weight: 80
url: /fr/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter.Delimit method

Délimite les arguments à l'aide du caractère délimiteur spécifié

```csharp
public IMathDelimiter Delimit(char separatorCharacter)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| separatorCharacter | Char | caractère délimiteur |

### Return_Value

Cet objet après application du caractère délimiteur

### Exemples

Exemple :

```csharp
[C#]
IMathDelimiter delimiter = new MathematicalText("x").Join("y").Enclose();
delimiter.Delimit('|');
```

### Voir également

* interface [IMathDelimiter](../../imathdelimiter)
* espace de noms [Aspose.Slides.MathText](../../imathdelimiter)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
