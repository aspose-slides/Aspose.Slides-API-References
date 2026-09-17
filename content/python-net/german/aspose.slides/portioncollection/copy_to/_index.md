---
title: copy_to method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
Kopiert die Elemente der **System.Collections.Generic.ICollection`1** in ein **System.Array**, beginnend bei einem bestimmten **System.Array**-Index.


```python
def copy_to(self, array, array_index):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| array | **List[IPortion]** | Der eindimensionale **System.Array**, der das Ziel der von **System.Collections.Generic.ICollection`1** kopierten Elemente ist. Der **System.Array** muss nullbasierte Indizierung besitzen. |
| array_index | **int** | Der nullbasierte Index in `array`, bei dem das Kopieren beginnt. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` ist None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` ist kleiner als 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Die Anzahl der Elemente in der Quell-**System.Collections.Generic.ICollection`1** ist größer als der verfügbare Platz von `array_index` bis zum Ende des Ziel-`array`. |



### Siehe auch
* Klasse [`PortionCollection`](/slides/python-net/de/aspose.slides/portioncollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)