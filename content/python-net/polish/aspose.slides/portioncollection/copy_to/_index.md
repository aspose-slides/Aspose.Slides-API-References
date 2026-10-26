---
title: copy_to method
second_title: Aspose.Slides dla Pythona przez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
Kopiuje elementy **System.Collections.Generic.ICollection`1** do **System.Array**, zaczynając od określonego indeksu **System.Array**.

```python
def copy_to(self, array, array_index):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| array | **List[IPortion]** | Jednowymiarowa **System.Array**, będąca miejscem docelowym elementów skopiowanych z **System.Collections.Generic.ICollection`1**. **System.Array** musi mieć indeksowanie zerowe. |
| array_index | **int** | Indeks zerowy w `array`, od którego rozpoczyna się kopiowanie. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` jest None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` jest mniejsze niż 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Liczba elementów w źródłowym **System.Collections.Generic.ICollection`1** jest większa niż dostępna przestrzeń od `array_index` do końca docelowego `array`. |

### Zobacz także
* klasa [`PortionCollection`](/slides/python-net/pl/aspose.slides/portioncollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)