---
title: remove_at method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/masterslidecollection/remove_at/
weight: 40
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
Pour éviter le déclenchement de PptxEditException, vérifiez la propriété HasDependingSlides du master avant.

### Exceptions
| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception) | Lancée si le master à supprimer est utilisé dans la présentation (sa propriété HasDependingSlides est vraie). |

### Voir aussi
* classe [`MasterSlideCollection`](/slides/python-net/fr/aspose.slides/masterslidecollection)
* classe [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)