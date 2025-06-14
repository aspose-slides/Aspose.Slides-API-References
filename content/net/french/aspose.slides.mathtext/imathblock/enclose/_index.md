---
title: Enclose
second_title: Aspose.Sildes pour .NET Référence de l'API
description: Enclot les éléments enfants de ce bloc dans des caractères spécifiés tels que des parenthèses ou un autre comme encadrement et délimite avec un caractère séparateur
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/imathblock/enclose/
---

## IMathBlock.Enclose méthode

Enclot les éléments enfants de ce bloc dans des caractères spécifiés tels que des parenthèses ou un autre comme encadrement et délimite avec un caractère séparateur

```csharp
public IMathDelimiter Enclose(char beginningCharacter, char endingCharacter, 
    char separatorCharacter)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| beginningCharacter | Char | Caractère de début (généralement crochet gauche) |
| endingCharacter | Char | Caractère de fin (généralement crochet droit) |
| separatorCharacter | Char | Caractère séparateur |

### Valeur de Retour

L'élément mathématique de type [`IMathDelimiter`](../../imathdelimiter) qui inclut les caractères spécifiés comme encadrement et délimiteur

### Exemples

Exemple:

```csharp
[C#]
IMathBlock mathBlock = new MathematicalText("x").Join("y");
IMathDelimiter delimiterElement = mathBlock.Enclose('{', '}', '%');
```

### Voir Aussi

* interface [IMathDelimiter](../../imathdelimiter)
* interface [IMathBlock](../../imathblock)
* namespace [Aspose.Slides.MathText](../../imathblock)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->