---
title: Contient
second_title: Référence de l'API Aspose.Slides pour .NET
description: Détermine si la collection contient une valeur spécifique.
type: docs
weight: 60
url: /fr/aspose.slides.mathtext/imathblockcollection/contains/
---

## IMathBlockCollection.Contains méthode

Détermine si la collection contient une valeur spécifique.

```csharp
public bool Contains(IMathBlock item)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| item | IMathBlock | L'objet à localiser dans la collection. |

### Valeur de retour

true si *item* est trouvé dans la collection ; sinon, false.

### Exemples

Exemple:

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
IMathBlock block = new MathBlock(new MathematicalText("y"));
blockCollection.Add(block);
bool contains = blockCollection.Contains(block);
```

### Voir aussi

* interface [IMathBlock](../../imathblock)
* interface [IMathBlockCollection](../../imathblockcollection)
* namespace [Aspose.Slides.MathText](../../imathblockcollection)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->