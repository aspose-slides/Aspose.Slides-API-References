---
title: insert_clone method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/imasterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Insère une copie d’une mise en page de diapositive spécifiée à la position indiquée de la collection.

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

Le nouveau layout sera lié à la diapositive maître parente pour cette collection de diapositives de mise en page. Ainsi, c’est l’analogue du copier/coller avec l’option "Use Destination Theme" dans PowerPoint.



### Voir aussi
* classe [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide)
* classe [`IMasterLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/imasterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)