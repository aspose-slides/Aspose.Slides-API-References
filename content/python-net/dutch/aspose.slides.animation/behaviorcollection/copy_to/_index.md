---
title: copy_to method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
Kopieert de elementen van de **System.Collections.Generic.ICollection`1** naar een **System.Array**, beginnend op een bepaalde **System.Array** index.


```python
def copy_to(self, array, array_index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| array | **List[IBehavior]** | De eendimensionale **System.Array** die de bestemming is van de elementen die gekopieerd zijn vanuit **System.Collections.Generic.ICollection`1**. De **System.Array** moet nulgebaseerde indexering hebben. |
| array_index | **int** | De nulgebaseerde index in `array` waarop het kopiëren begint. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` is None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` is kleiner dan 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Het aantal elementen in de bron **System.Collections.Generic.ICollection`1** is groter dan de beschikbare ruimte vanaf `array_index` tot het einde van de bestemmings-`array`. |



### Zie ook
* klasse [`BehaviorCollection`](/slides/python-net/nl/aspose.slides.animation/behaviorcollection)
* module [`aspose.slides.animation`](/slides/python-net/nl/aspose.slides.animation)
* bibliotheek [`Aspose.Slides`](/slides/python-net)