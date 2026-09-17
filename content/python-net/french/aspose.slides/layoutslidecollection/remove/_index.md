---
title: remove method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/layoutslidecollection/remove/
weight: 20
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

1) Pour éviter le déclenchement de PptxEditException, vérifiez la propriété HasDependingSlides de la mise en page au préalable.
2) Vous pouvez également utiliser la méthode [`ILayoutSlide.remove`](/slides/python-net/fr/aspose.slides/ilayoutslide/remove) pour simplifier le code.

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception) | Lancée si la mise en page est utilisée dans la présentation (sa propriété HasDependingSlides est vraie). |



### Voir aussi
* classe [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide)
* classe [`LayoutSlideCollection`](/slides/python-net/fr/aspose.slides/layoutslidecollection)
* classe [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)