---
title: Supprimer
second_title: Aspose.Slides pour .NET Référence API
description: Supprime une mise en page de la collection.
type: docs
weight: 80
url: /fr/aspose.slides/layoutslidecollection/remove/
---

## LayoutSlideCollection.Remove méthode

Supprime une mise en page de la collection.

```csharp
public void Remove(ILayoutSlide value)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| value | ILayoutSlide | La mise en page à supprimer de la collection. |

### Exceptions

| exception | condition |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Lancée si la mise en page est utilisée dans la présentation (sa propriété HasDependingSlides est vraie). |

### Remarques

1) Pour éviter de lancer la PptxEditException, vérifiez la propriété HasDependingSlides de la mise en page au préalable. 2) Vous pouvez également utiliser la méthode [`Remove`](../../ilayoutslide/remove) pour simplifier le code.

### Voir aussi

* interface [ILayoutSlide](../../ilayoutslide)
* class [LayoutSlideCollection](../../layoutslidecollection)
* namespace [Aspose.Slides](../../layoutslidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->