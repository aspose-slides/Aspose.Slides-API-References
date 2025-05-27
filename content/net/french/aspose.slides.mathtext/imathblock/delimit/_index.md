---
title: Délimiter
second_title: Référence de l'API Aspose.Slides pour .NET
description: Délimite tous les éléments enfants avec un caractère séparateur sans les crochets
type: docs
weight: 30
url: /fr/aspose.slides.mathtext/imathblock/delimit/
---

## IMathBlock.Delimit méthode

Délimite tous les éléments enfants avec un caractère séparateur (sans les crochets)

```csharp
public IMathDelimiter Delimit(char separatorCharacter)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| separatorCharacter | Char | Caractère utilisé comme séparateur |

### Valeur de retour

Instance de l'élément IMathDelimiter

### Exemples

Exemple:

```csharp
[C#]
IMathBlock mathBlock = new MathematicalText("x").Join("y");
IMathDelimiter delimiterElement = mathBlock.Delimit('|');
```

### Voir aussi

* interface [IMathDelimiter](../../imathdelimiter)
* interface [IMathBlock](../../imathblock)
* namespace [Aspose.Slides.MathText](../../imathblock)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour Aspose.Slides.dll -->