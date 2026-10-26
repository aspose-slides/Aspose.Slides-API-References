---
title: remove method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/commentauthorcollection/remove/
weight: 50
---
## remove(self, author) {#icommentauthor}
Supprime la première occurrence de l'auteur spécifié dans une collection.

```python
def remove(self, author):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| author | [`ICommentAuthor`](/slides/python-net/fr/aspose.slides/icommentauthor) | L'auteur à supprimer d'une collection. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | L'auteur est `None` |
| [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception) | Lancé si l'auteur a déjà été supprimé. |

### Voir aussi
* classe [`CommentAuthorCollection`](/slides/python-net/fr/aspose.slides/commentauthorcollection)
* classe [`ICommentAuthor`](/slides/python-net/fr/aspose.slides/icommentauthor)
* classe [`PptxEditException`](/slides/python-net/fr/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)