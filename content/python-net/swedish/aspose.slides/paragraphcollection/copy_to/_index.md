---
title: copy_to method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
Kopierar elementen i **System.Collections.Generic.ICollection`1** till en **System.Array**, med start vid ett specifikt **System.Array** index.

```python
def copy_to(self, array, array_index):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| array | **List[IParagraph]** | Den endimensionella **System.Array** som är mottagaren av elementen som kopierats från **System.Collections.Generic.ICollection`1**. **System.Array** måste ha nollbaserad indexering. |
| array_index | **int** | Det nollbaserade indexet i `array` där kopieringen börjar. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` är None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` är mindre än 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Antalet element i källan **System.Collections.Generic.ICollection`1** är större än det tillgängliga utrymmet från `array_index` till slutet av destinationens `array`. |

### Se även
* klass [`ParagraphCollection`](/slides/python-net/sv/aspose.slides/paragraphcollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)