---
title: remove method
second_title: Aspose.Slides pour Python via l'API .NET
description: 
type: docs
url: /fr/aspose.slides/masterlayoutslidecollection/remove/
weight: 60
---
## remove(self, value) {#ilayoutslide}
Supprime une mise en page de la collection.

```python
def remove(self, value):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide) | La diapositive de mise en page à supprimer de la collection. |

### Remarques

1) Pour éviter le déclenchement de la PptxEditException, vérifiez la propriété HasDependingSlides de la mise en page au préalable.  
2) Vous pouvez également utiliser la méthode [`ILayoutSlide.remove`](/slides/python-net/fr/aspose.slides/ilayoutslide/remove) pour simplifier le code.

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception) | Lancée si la mise en page est utilisée dans la présentation (sa propriété HasDependingSlides est vraie). |

### Voir aussi
* classe [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide)
* classe [`MasterLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/masterlayoutslidecollection)
* classe [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)