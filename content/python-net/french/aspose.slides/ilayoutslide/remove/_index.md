---
title: remove method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ilayoutslide/remove/
weight: 60
---
## remove(self) {#}
Supprime la disposition de la présentation.

```python
def remove(self):
    ...
```

### Remarques

Pour éviter le déclenchement de la PptxEditException, vérifiez la propriété HasDependingSlides du layout au préalable.

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception) | Lancée si le layout a déjà été retiré de la présentation ou si le layout est utilisé dans la présentation (sa <br/>            HasDependingSlides propriété est vraie). |

### Voir aussi
* classe [`ILayoutSlide`](/slides/python-net/fr/aspose.slides/ilayoutslide)
* classe [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)