---
title: contains method
second_title: Aspose.Slides dla Pythona poprzez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
Określa, czy podany punkt znajduje się wewnątrz tego prostokąta.

### Zwraca

`True` jeśli punkt znajduje się wewnątrz tego prostokąta; w przeciwnym razie `False`.



```python
def contains(self, point):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/pl/aspose.slides/pointf) | Punkt do przetestowania. Akceptowany jest każdy obiekt posiadający atrybuty `x` i `y`. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **TypeError** | Nieprawidłowa liczba argumentów. |


## contains(self, rect) {#rectanglef}
Określa, czy obszar prostokątny reprezentowany przez `rect` jest całkowicie zawarty w tym prostokącie.

### Zwraca

`True` jeśli obszar prostokątny reprezentowany przez `rect` jest całkowicie zawarty w tym prostokącie; w przeciwnym razie `False`.



```python
def contains(self, rect):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef) | Prostokąt do przetestowania. Akceptowany jest każdy obiekt posiadający atrybuty `x`, `y`, `width` i `height`. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **TypeError** | Nieprawidłowa liczba argumentów. |


## contains(self, x, y) {#float-float}
Określa, czy podany punkt znajduje się wewnątrz tego prostokąta.

### Zwraca

`True` jeśli punkt określony przez `x` i `y` znajduje się wewnątrz tego prostokąta; w przeciwnym razie `False`.



```python
def contains(self, x, y):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| x | **float** | Współrzędna x punktu do przetestowania. |
| y | **float** | Współrzędna y punktu do przetestowania. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **TypeError** | Nieprawidłowa liczba argumentów. |



### Zobacz także
* klasa [`PointF`](/slides/python-net/pl/aspose.slides/pointf)
* klasa [`RectangleF`](/slides/python-net/pl/aspose.slides/rectanglef)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)