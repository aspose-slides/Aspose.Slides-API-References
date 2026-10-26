---
title: contains method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
Bepaalt of het opgegeven punt zich binnen dit rechthoek bevindt.

### Retourwaarde

`True` als het punt zich binnen dit rechthoek bevindt; anders `False`.

```python
def contains(self, point):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/nl/aspose.slides/point) | Het te testen punt. Elk object met `x`- en `y`-attributen wordt geaccepteerd. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **TypeError** | Verkeerd aantal argumenten. |

## contains(self, rect) {#rectangle}
Bepaalt of het rechthoekige gebied vertegenwoordigd door `rect` volledig binnen dit rechthoek ligt.

### Retourwaarde

`True` als het door `rect` vertegenwoordigde rechthoekige gebied volledig binnen dit rechthoek ligt; anders `False`.

```python
def contains(self, rect):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/nl/aspose.slides/rectangle) | Het te testen rechthoek. Elk object met `x`, `y`, `width` en `height`-attributen wordt geaccepteerd. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **TypeError** | Verkeerd aantal argumenten. |

## contains(self, x, y) {#int-int}
Bepaalt of het opgegeven punt zich binnen dit rechthoek bevindt.

### Retourwaarde

`True` als het door `x` en `y` gedefinieerde punt zich binnen dit rechthoek bevindt; anders `False`.

```python
def contains(self, x, y):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | **int** | De x-coördinaat van het te testen punt. |
| y | **int** | De y-coördinaat van het te testen punt. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **TypeError** | Verkeerd aantal argumenten. |

### Zie ook
* klasse [`Point`](/slides/python-net/nl/aspose.slides/point)
* klasse [`Rectangle`](/slides/python-net/nl/aspose.slides/rectangle)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)