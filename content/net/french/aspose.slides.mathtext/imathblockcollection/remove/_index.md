---
title: Remove
second_title: Référence de l'API Aspose.Slides pour .NET
description: Supprime la première occurrence dun objet spécifique de la collection/gt.
type: docs
weight: 90
url: /fr/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection.Remove method

Supprime la première occurrence d'un objet spécifique de la collection/&gt;.

```csharp
public bool Remove(IMathBlock item)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| item | IMathBlock | Objet à supprimer de la collection. |

### Return_Value

vrai si*item* a été supprimé avec succès de la collection ; sinon, faux. Cette méthode renvoie également false si*item* est introuvable dans la collection d'origine/&gt;.

### Exemples

Exemple :

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
IMathBlock block = new MathBlock(new MathematicalText("y"));
blockCollection.Add(block);
blockCollection.Remove(block);
```

### Voir également

* interface [IMathBlock](../../imathblock)
* interface [IMathBlockCollection](../../imathblockcollection)
* espace de noms [Aspose.Slides.MathText](../../imathblockcollection)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
