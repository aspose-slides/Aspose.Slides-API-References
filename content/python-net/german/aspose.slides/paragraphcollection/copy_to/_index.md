---
title: copy_to method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
Kopiert die Elemente der **System.Collections.Generic.ICollection`1** in ein **System.Array**, beginnend an einem bestimmten **System.Array**-Index.

```python
def copy_to(self, array, array_index):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| array | **List[IParagraph]** | Das eindimensionale **System.Array**, das das Ziel der aus **System.Collections.Generic.ICollection`1** kopierten Elemente ist. Das **System.Array** muss nullbasierte Indizierung haben. |
| array_index | **int** | Der nullbasierte Index in `array`, bei dem das Kopieren beginnt. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` ist None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` ist kleiner als 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Die Anzahl der Elemente in der Quell-**System.Collections.Generic.ICollection`1** ist größer als der verfügbare Platz von `array_index` bis zum Ende des Ziel-`array`. |

### Siehe auch
* Klasse [`ParagraphCollection`](/slides/python-net/de/aspose.slides/paragraphcollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)