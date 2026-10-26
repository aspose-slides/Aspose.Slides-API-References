---
title: copy_to method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
Kopierar elementen i **System.Collections.Generic.ICollection`1** till en **System.Array**, med start vid ett specifikt **System.Array**-index.


```python
def copy_to(self, array, array_index):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| array | **List[IPortion]** | Den endimensionella **System.Array** som är målet för de element som kopierats från **System.Collections.Generic.ICollection`1**. **System.Array** måste ha nollbaserad indexering. |
| array_index | **int** | Det nollbaserade indexet i `array` där kopieringen börjar. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` är None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` är mindre än 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Antalet element i källan **System.Collections.Generic.ICollection`1** är större än det tillgängliga utrymmet från `array_index` till slutet av destinations-`array`. |

### Se även
* klass [`PortionCollection`](/slides/python-net/sv/aspose.slides/portioncollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)