---
title: RemoveAt
second_title: Référence de l'API Aspose.Slides pour .NET
description: Supprime l'élément à l'index spécifié de la collection.
type: docs
weight: 100
url: /fr/aspose.slides/masterslidecollection/removeat/
---

## MasterSlideCollection.RemoveAt méthode

Supprime l'élément à l'index spécifié de la collection.

```csharp
public void RemoveAt(int index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | L'index basé sur zéro de l'élément à supprimer. |

### Exceptions

| exception | condition |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Déclenchée si le maître à supprimer est utilisé dans la présentation (sa propriété HasDependingSlides est vraie). |

### Remarques

Pour éviter de déclencher l'exception PptxEditException, vérifiez la propriété HasDependingSlides du maître au préalable.

### Voir aussi

* class [MasterSlideCollection](../../masterslidecollection)
* namespace [Aspose.Slides](../../masterslidecollection)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour Aspose.Slides.dll -->