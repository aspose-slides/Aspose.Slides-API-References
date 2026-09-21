---
title: copy_to method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
Kopieert de elementen van de **System.Collections.Generic.ICollection`1** naar een **System.Array**, beginnend bij een bepaalde **System.Array**-index.


```python
def copy_to(self, array, array_index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| array | **List[IPortion]** | De eendimensionale **System.Array** die de bestemming is van de elementen die gekopieerd worden vanuit **System.Collections.Generic.ICollection`1**. De **System.Array** moet een nulgebaseerde indexering hebben. |
| array_index | **int** | De nulgebaseerde index in `array` waarop het kopiëren begint. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` is None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` is kleiner dan 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Het aantal elementen in de bron **System.Collections.Generic.ICollection`1** is groter dan de beschikbare ruimte vanaf `array_index` tot het einde van de bestemmings-`array`. |



### Zie ook
* klasse [`PortionCollection`](/slides/python-net/nl/aspose.slides/portioncollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)