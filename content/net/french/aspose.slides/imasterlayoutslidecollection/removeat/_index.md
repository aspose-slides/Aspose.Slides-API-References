---
title: RemoveAt
second_title: Aspose.Slides pour .NET Référence API
description: Supprime l'élément à l'index spécifié de la collection.
type: docs
weight: 60
url: /fr/aspose.slides/imasterlayoutslidecollection/removeat/
---

## IMasterLayoutSlideCollection.RemoveAt méthode

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
| [PptxEditException](../../pptxeditexception) | Levé si la mise en page est utilisée dans la présentation (la propriété HasDependingSlides est vraie). |

### Remarques

1) Pour éviter le lancement de PptxEditException, vérifiez d'abord la propriété HasDependingSlides de la mise en page. 2) Vous pouvez également utiliser la méthode [`Remove`](../../ilayoutslide/remove) pour simplifier le code.

### Voir aussi

* interface [IMasterLayoutSlideCollection](../../imasterlayoutslidecollection)
* namespace [Aspose.Slides](../../imasterlayoutslidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->