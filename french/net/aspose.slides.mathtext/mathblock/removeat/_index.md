---
title: RemoveAt
second_title: Référence de l'API Aspose.Slides pour .NET
description: Supprime lélément à lindex spécifié de la collection.
type: docs
weight: 170
url: /fr/net/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock.RemoveAt method

Supprime l'élément à l'index spécifié de la collection.

```csharp
public void RemoveAt(int index)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| index | Int32 | Index de base zéro de l'élément à supprimer. |

### Exemples

Exemple :

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
mathBlock.Add(plusElement);
mathBlock.Insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
mathBlock.RemoveAt(2);
```

### Voir également

* class [MathBlock](../../mathblock)
* espace de noms [Aspose.Slides.MathText](../../mathblock)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->