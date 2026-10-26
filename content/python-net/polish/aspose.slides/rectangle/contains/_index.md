---
title: contains method
second_title: Aspose.Slides dla Pythona poprzez .NET – referencja API
description: 
type: docs
url: /pl/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
Określa, czy podany punkt znajduje się w tym prostokącie.

### Returns

`True` jeśli punkt znajduje się w tym prostokącie; w przeciwnym razie `False`.



```python
def contains(self, point):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/pl/aspose.slides/point) | Punkt do przetestowania. Akceptowany jest każdy obiekt posiadający atrybuty `x` i `y`. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **TypeError** | Nieprawidłowa liczba argumentów. |


## contains(self, rect) {#rectangle}
Określa, czy obszar prostokątny reprezentowany przez `rect` jest całkowicie zawarty w tym prostokącie.

### Returns

`True` jeśli obszar prostokątny reprezentowany przez `rect` jest całkowicie zawarty w tym prostokącie; w przeciwnym razie `False`.



```python
def contains(self, rect):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/pl/aspose.slides/rectangle) | Prostokąt do przetestowania. Akceptowany jest każdy obiekt posiadający atrybuty `x`, `y`, `width` i `height`. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **TypeError** | Nieprawidłowa liczba argumentów. |


## contains(self, x, y) {#int-int}
Określa, czy podany punkt znajduje się w tym prostokącie.

### Returns

`True` jeśli punkt określony przez `x` i `y` znajduje się w tym prostokącie; w przeciwnym razie `False`.



```python
def contains(self, x, y):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| x | **int** | Współrzędna x punktu do przetestowania. |
| y | **int** | Współrzędna y punktu do przetestowania. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **TypeError** | Nieprawidłowa liczba argumentów. |



### Zobacz także
* klasa [`Point`](/slides/python-net/pl/aspose.slides/point)
* klasa [`Rectangle`](/slides/python-net/pl/aspose.slides/rectangle)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)