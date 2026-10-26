---
title: copy_to method
second_title: Aspose.Slides dla Pythona przez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
Kopiuje elementy **System.Collections.Generic.ICollection`1** do **System.Array**, zaczynając od określonego indeksu **System.Array**.


```python
def copy_to(self, array, array_index):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| array | **List[IParagraph]** | Jednowymiarowa **System.Array**, która jest miejscem docelowym elementów skopiowanych z **System.Collections.Generic.ICollection`1**. **System.Array** musi mieć indeksowanie od zera. |
| array_index | **int** | Indeks bazujący na zerze w `array`, od którego rozpoczyna się kopiowanie. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` jest None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` jest mniejszy niż 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Liczba elementów w źródłowym **System.Collections.Generic.ICollection`1** jest większa niż dostępna przestrzeń od `array_index` do końca docelowego `array`. |



### Zobacz także
* klasa [`ParagraphCollection`](/slides/python-net/pl/aspose.slides/paragraphcollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)