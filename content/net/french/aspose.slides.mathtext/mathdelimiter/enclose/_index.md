---
title: Enclose
second_title: Aspose.Sildes pour .NET Référence API
description: Enclot un élément mathématique dans des caractères spécifiés tels que des parenthèses ou d'autres caractères comme encadrement
type: docs
weight: 90
url: /fr/aspose.slides.mathtext/mathdelimiter/enclose/
---

## MathDelimiter.Enclose méthode

Enclot un élément mathématique dans des caractères spécifiés tels que des parenthèses ou d'autres caractères comme encadrement

```csharp
public override IMathDelimiter Enclose(char beginningCharacter, char endingCharacter)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| beginningCharacter | Char | Caractère de début (généralement crochets gauche) |
| endingCharacter | Char | Caractère de fin (généralement crochets droit) |

### Valeur de retour

Si *beginningCharacter* et *endingCharacter* sont null, les propriétés correspondantes se voient attribuer des valeurs uniquement et aucun nouvel objet n'est créé (retourne cette instance). Sinon, retourne un nouvel élément mathématique de type Delimiter qui inclut les caractères spécifiés comme encadrement et cette instance de [`MathDelimiter`](../../mathdelimiter) encadrée à l'intérieur.

### Exemples

Exemple:

```csharp
[C#]
IMathDelimiter innerDelimiter = new MathematicalText("x").Join(",y").Enclose('{', '}');
IMathDelimiter outerDelimiter = innerDelimiter.Enclose('[', ']');
```

### Voir aussi

* interface [IMathDelimiter](../../imathdelimiter)
* classe [MathDelimiter](../../mathdelimiter)
* espace de noms [Aspose.Slides.MathText](../../mathdelimiter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->