---
title: Contains
second_title: Référence de l'API Aspose.Slides pour .NET
description: Détermine si la collection contient une valeur spécifique.
type: docs
weight: 60
url: /fr/aspose.slides.mathtext/imathblockcollection/contains/
---
## IMathBlockCollection.Contains method

Détermine si la collection contient une valeur spécifique.

```csharp
public bool Contains(IMathBlock item)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| item | IMathBlock | Objet à localiser dans la collection. |

### Return_Value

vrai si*item* se trouve dans la collection; sinon, faux.

### Exemples

Exemple :

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
IMathBlock block = new MathBlock(new MathematicalText("y"));
blockCollection.Add(block);
bool contains = blockCollection.Contains(block);
```

### Voir également

* interface [IMathBlock](../../imathblock)
* interface [IMathBlockCollection](../../imathblockcollection)
* espace de noms [Aspose.Slides.MathText](../../imathblockcollection)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
