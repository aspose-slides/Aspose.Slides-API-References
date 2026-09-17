---
title: delete_column method
second_title: Aspose.Slides pour Python via la référence d'API .NET
description: 
type: docs
url: /fr/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
Supprime la colonne spécifiée


```python
def delete_column(self, column_index):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| column_index | **int** | L'index basé sur zéro de la colonne à supprimer. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lorsque vous essayez de supprimer la dernière colonne unique de la matrice |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Si columnIndex est inférieur à zéro ou supérieur ou égal à ColumnCount |



### Voir aussi
* classe [`MathMatrix`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix)
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)