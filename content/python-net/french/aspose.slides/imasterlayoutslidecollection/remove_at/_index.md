---
title: remove_at method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/imasterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Supprime l'élément à l'index spécifié de la collection.


```python
def remove_at(self, index):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L'index basé sur zéro de l'élément à supprimer. |

### Remarques

1) Pour éviter le déclenchement de la PptxEditException, vérifiez d'abord la propriété HasDependingSlides du layout.  
2) Vous pouvez également utiliser la méthode [`ILayoutSlide.remove`](/slides/python-net/fr/aspose.slides/ilayoutslide/remove) pour simplifier le code.

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception) | Lancée si le layout est utilisé dans la présentation (sa propriété HasDependingSlides est vraie). |



### Voir aussi
* classe [`IMasterLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/imasterlayoutslidecollection)
* classe [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)