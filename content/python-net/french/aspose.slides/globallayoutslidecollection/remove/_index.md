---
title: remove method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/globallayoutslidecollection/remove/
weight: 40
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

1) Pour éviter le lancement de PptxEditException, vérifiez d'abord la propriété HasDependingSlides de la mise en page.
2) Vous pouvez également utiliser la méthode [`ILayoutSlide.remove`](/slides/python-net/fr/aspose.slides/ilayoutslide/remove) pour simplifier le code.

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception) | Levée si la mise en page est utilisée dans la présentation (sa propriété HasDependingSlides est vraie). |

### Voir aussi
* classe [`GlobalLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/globallayoutslidecollection)
* classe [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide)
* classe [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)