---
title: insert_clone method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Insère une copie d’une diapositive de disposition spécifiée à la position indiquée de la collection.

### Retour
Diapositive insérée.

```python
def insert_clone(self, index, source_layout):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | Index de la nouvelle diapositive. |
| source_layout | [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide) | Diapositive à cloner. |

### Remarques
La nouvelle disposition sera liée à la diapositive maître parente pour cette collection de diapositives de disposition.
            C’est donc l’équivalent de copier/coller avec l’option « Use Destination Theme » dans PowerPoint.

### Voir aussi
* classe [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide)
* classe [`MasterLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/masterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)