---
title: RemoveAt
second_title: Référence de l'API Aspose.Slides pour .NET
description: Supprime lélément à lindex spécifié de la collection.
type: docs
weight: 50
url: /fr/net/aspose.slides/masterlayoutslidecollection/removeat/
---
## MasterLayoutSlideCollection.RemoveAt method

Supprime l'élément à l'index spécifié de la collection.

```csharp
public void RemoveAt(int index)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| index | Int32 | Index de base zéro de l'élément à supprimer. |

### Exceptions

| exception | condition |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Levé si la mise en page est utilisée dans la présentation (sa propriété HasDependingSlides est vraie). |

### Remarques

1) Pour éviter de lancer la propriété HasDependingSlides de la disposition de vérification PptxEditException avant. 2) Vous pouvez également utiliser[`Remove`](../../ilayoutslide/remove) méthode pour simplifier le code.

### Voir également

* class [MasterLayoutSlideCollection](../../masterlayoutslidecollection)
* espace de noms [Aspose.Slides](../../masterlayoutslidecollection)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->