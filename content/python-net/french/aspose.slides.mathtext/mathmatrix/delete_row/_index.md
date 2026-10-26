---
title: delete_row method
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
Supprime la ligne spécifiée


```python
def delete_row(self, row_index):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| row_index | **int** | L'indice basé sur zéro de la ligne à supprimer. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lorsque vous essayez de supprimer la dernière ligne unique de la matrice |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Si rowIndex est inférieur à zéro ou supérieur ou égal à RowCount |



### Voir aussi
* classe [`MathMatrix`](/slides/python-net/fr/aspose.slides.mathtext/mathmatrix)
* module [`aspose.slides.mathtext`](/slides/python-net/fr/aspose.slides.mathtext)
* bibliothèque [`Aspose.Slides`](/slides/python-net)