---
title: copy_to method
second_title: Aspose.Slides pour Python via la référence d'API .NET
description: 
type: docs
url: /fr/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
Copie les éléments de la **System.Collections.Generic.ICollection`1** dans un **System.Array**, en commençant à un indice particulier du **System.Array**.


```python
def copy_to(self, array, array_index):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| array | **List[IPortion]** | Le **System.Array** unidimensionnel qui est la destination des éléments copiés depuis **System.Collections.Generic.ICollection`1**. Le **System.Array** doit être indexé à partir de zéro. |
| array_index | **int** | L'indice basé sur zéro dans `array` où la copie commence. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` est None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` est inférieur à 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Le nombre d'éléments dans la source **System.Collections.Generic.ICollection`1** est supérieur à l'espace disponible depuis `array_index` jusqu'à la fin du **System.Array** de destination. |



### Voir aussi
* classe [`PortionCollection`](/slides/python-net/fr/aspose.slides/portioncollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)