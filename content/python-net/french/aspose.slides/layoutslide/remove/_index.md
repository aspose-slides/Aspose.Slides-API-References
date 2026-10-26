---
title: remove method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/layoutslide/remove/
weight: 60
---
## remove(self) {#}
Supprime la disposition de la présentation.

```python
def remove(self):
    ...
```

### Remarques

Pour éviter le lancement de la PptxEditException, vérifiez la propriété HasDependingSlides de la disposition au préalable.

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception) | Lancée si la disposition a déjà été supprimée de la présentation ou si la disposition est utilisée dans la présentation (sa propriété HasDependingSlides est vraie). |

### Voir aussi
* classe [`LayoutSlide`](/slides/python-net/fr/aspose.slides/layoutslide)
* classe [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)