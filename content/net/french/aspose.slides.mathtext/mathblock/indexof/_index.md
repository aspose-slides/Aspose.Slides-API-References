---
title: IndexOf
second_title: Aspose.Sildes pour .NET Référence de l'API
description: Détermine l'index d'un élément mathématique spécifique dans la collection.
type: docs
weight: 120
url: /fr/aspose.slides.mathtext/mathblock/indexof/
---

## Méthode MathBlock.IndexOf

Détermine l'index d'un élément mathématique spécifique dans la collection.

```csharp
public int IndexOf(IMathElement item)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| item | IMathElement | L'élément à localiser dans la collection. |

### Valeur de retour

L'index de *item* s'il est trouvé dans la collection ; sinon, -1.

### Exemples

Exemple :

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
mathBlock.Add(plusElement);
mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
int index = mathBlock.IndexOf(plusElement);
```

### Voir aussi

* interface [IMathElement](../../imathelement)
* class [MathBlock](../../mathblock)
* namespace [Aspose.Slides.MathText](../../mathblock)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->