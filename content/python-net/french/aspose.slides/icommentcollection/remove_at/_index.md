---
title: remove_at method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/icommentcollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Supprime l'élément à l'index spécifié dans une collection.

```python
def remove_at(self, index):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L'index basé sur zéro de l'élément à supprimer. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | L'index est inférieur à 0 ou l'index est égal ou supérieur à Count |
| [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception) | Levée si le commentaire est déjà supprimé. |

### Voir aussi
* classe [`ICommentCollection`](/slides/python-net/fr/aspose.slides/icommentcollection)
* classe [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)