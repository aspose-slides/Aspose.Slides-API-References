---
title: copy_to method
second_title: Aspose.Slides pro Python přes .NET - referenční příručka API
description: 
type: docs
url: /cs/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
Kopíruje prvky **System.Collections.Generic.ICollection`1** do **System.Array**, počínaje konkrétním indexem **System.Array**.


```python
def copy_to(self, array, array_index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| array | **List[IBehavior]** | Jednorozměrné **System.Array**, které je cílem prvků zkopírovaných z **System.Collections.Generic.ICollection`1**. **System.Array** musí mít nulové indexování. |
| array_index | **int** | Nulový index v `array`, od kterého začíná kopírování. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` je None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` je menší než 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Počet prvků ve zdrojovém **System.Collections.Generic.ICollection`1** je větší než dostupný prostor od `array_index` do konce cílového `array`. |



### Viz také
* třída [`BehaviorCollection`](/slides/python-net/cs/aspose.slides.animation/behaviorcollection)
* modul [`aspose.slides.animation`](/slides/python-net/cs/aspose.slides.animation)
* knihovna [`Aspose.Slides`](/slides/python-net)