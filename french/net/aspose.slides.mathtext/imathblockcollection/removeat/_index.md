---
title: RemoveAt
second_title: Référence de l'API Aspose.Slides pour .NET
description: Supprime un élément à lindex spécifié de la collection.
type: docs
weight: 100
url: /fr/net/aspose.slides.mathtext/imathblockcollection/removeat/
---
## IMathBlockCollection.RemoveAt method

Supprime un élément à l'index spécifié de la collection.

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
IMathBlockCollection blockCollection = new MathParagraph();
IMathBlock block = new MathBlock(new MathematicalText("y"));
blockCollection.Add(block);
blockCollection.RemoveAt(0);
```

### Voir également

* interface [IMathBlockCollection](../../imathblockcollection)
* espace de noms [Aspose.Slides.MathText](../../imathblockcollection)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->