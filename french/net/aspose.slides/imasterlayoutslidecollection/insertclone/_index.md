---
title: InsertClone
second_title: Référence de l'API Aspose.Slides pour .NET
description: Insère une copie dune diapositive de mise en page spécifiée à la position spécifiée de la collection.
type: docs
weight: 50
url: /fr/net/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection.InsertClone method

Insère une copie d'une diapositive de mise en page spécifiée à la position spécifiée de la collection.

```csharp
public ILayoutSlide InsertClone(int index, ILayoutSlide sourceLayout)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| index | Int32 | Index de la nouvelle diapositive. |
| sourceLayout | ILayoutSlide | Faites glisser pour cloner. |

### Return_Value

Diapositive insérée.

### Remarques

La nouvelle mise en page sera liée à la diapositive principale parente pour cette collection de diapositives de mise en page. Il s'agit donc d'un copier/coller avec l'option "Utiliser le thème de destination" dans PowerPoint.

### Voir également

* interface [ILayoutSlide](../../ilayoutslide)
* interface [IMasterLayoutSlideCollection](../../imasterlayoutslidecollection)
* espace de noms [Aspose.Slides](../../imasterlayoutslidecollection)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->