---
title: InsertClone()
second_title: Référence API Aspose.Slides pour C++
description: Insère une copie d’une diapositive de mise en page spécifiée à la position indiquée de la collection.
type: docs
weight: 14
url: /fr/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) méthode

Insère une copie d’une diapositive de mise en page spécifiée à la position indiquée de la collection.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index de la nouvelle diapositive. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) à cloner. |

### Valeur de retour

Diapositive insérée.

## Remarques

Le nouveau plan sera lié à la diapositive maîtresse parente pour cette collection de diapositives de mise en page. Ainsi, c’est l’équivalent de copier/coller avec l’option "Use Destination Theme" dans PowerPoint.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [IMasterLayoutSlideCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)