---
title: copy_to method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
Zkopíruje prvky **System.Collections.Generic.ICollection`1** do **System.Array**, počínaje konkrétním indexem **System.Array**.

```python
def copy_to(self, array, array_index):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| array | **List[IPortion]** | Jednorozměrné **System.Array**, které je cílovým polem pro prvky zkopírované z **System.Collections.Generic.ICollection`1**. **System.Array** musí mít indexování začínající od nuly. |
| array_index | **int** | Index založený na nule v `array`, kde začíná kopírování. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` je None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` je menší než 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Počet prvků ve zdrojovém **System.Collections.Generic.ICollection`1** je větší než dostupný prostor od `array_index` do konce cílového `array`. |

### Viz také
* třída [`PortionCollection`](/slides/python-net/cs/aspose.slides/portioncollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)