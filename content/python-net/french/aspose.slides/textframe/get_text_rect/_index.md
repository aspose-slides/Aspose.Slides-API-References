---
title: get_text_rect method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/textframe/get_text_rect/
weight: 10
---
## get_text_rect(self) {#}
Obtient le rectangle de texte défini par la géométrie de la forme parente.

### Renvoie

Un [`RectangleF`](/slides/python-net/fr/aspose.slides/rectanglef) qui définit la zone de texte.



```python
def get_text_rect(self):
    ...
```


### Remarques

Les coordonnées du rectangle sont relatives au coin supérieur gauche de la forme parente.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Le cadre de texte n'est pas associé à une forme géométrique. |



### Voir aussi
* classe [`TextFrame`](/slides/python-net/fr/aspose.slides/textframe)
* classe [`RectangleF`](/slides/python-net/fr/aspose.slides/rectanglef)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)