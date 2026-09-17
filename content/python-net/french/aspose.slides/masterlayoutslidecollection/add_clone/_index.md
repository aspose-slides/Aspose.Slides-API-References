---
title: add_clone method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Ajoute une copie d'une diapositive de mise en page spécifiée à la fin de la collection.

### Retour
Diapositive ajoutée.

```python
def add_clone(self, source_layout):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide) | Diapositive à cloner. |

### Remarques
1) Le nouveau layout sera lié à la diapositive maître parente pour cette collection de diapositives de layout.
            Ainsi, c'est l'analogue de copier/coller avec l'option "Use Destination Theme" dans PowerPoint.
            2) L'analogue de cette méthode est la méthode **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide**
            accessible via la propriété [`IPresentation.layout_slides`](/slides/python-net/fr/aspose.slides/ipresentation/layout_slides).

### Voir aussi
* classe [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide)
* classe [`MasterLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/masterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)