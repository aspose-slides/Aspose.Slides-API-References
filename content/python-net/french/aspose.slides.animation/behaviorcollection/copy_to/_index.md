---
title: copy_to method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
Copie les éléments de la **System.Collections.Generic.ICollection`1** vers un **System.Array**, en commençant à un indice particulier du **System.Array**.


```python
def copy_to(self, array, array_index):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| array | **List[IBehavior]** | Le **System.Array** à une dimension qui est la destination des éléments copiés depuis **System.Collections.Generic.ICollection`1**. Le **System.Array** doit avoir un indexage à base zéro. |
| array_index | **int** | L'index à base zéro dans `array` où la copie commence. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` est None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` est inférieur à 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Le nombre d'éléments dans la source **System.Collections.Generic.ICollection`1** est supérieur à l'espace disponible depuis `array_index` jusqu'à la fin du `array` de destination. |



### Voir aussi
* classe [`BehaviorCollection`](/slides/python-net/fr/aspose.slides.animation/behaviorcollection)
* module [`aspose.slides.animation`](/slides/python-net/fr/aspose.slides.animation)
* bibliothèque [`Aspose.Slides`](/slides/python-net)