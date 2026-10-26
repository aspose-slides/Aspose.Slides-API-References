---
title: copy_to method
second_title: Aspose.Slides pour Python via la référence d'API .NET
description: 
type: docs
url: /fr/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
Copie les éléments de la **System.Collections.Generic.ICollection`1** vers un **System.Array**, en commençant à un indice particulier du **System.Array**.


```python
def copy_to(self, array, array_index):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| array | **List[IParagraph]** | Le **System.Array** unidimensionnel qui est la destination des éléments copiés depuis **System.Collections.Generic.ICollection`1**. Le **System.Array** doit avoir un indexage à base zéro. |
| array_index | **int** | L'indice basé sur zéro dans `array` auquel la copie commence. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` est None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` est inférieur à 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Le nombre d'éléments dans la source **System.Collections.Generic.ICollection`1** est supérieur à l'espace disponible de `array_index` jusqu'à la fin du `array` de destination. |



### Voir aussi
* classe [`ParagraphCollection`](/slides/python-net/fr/aspose.slides/paragraphcollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)