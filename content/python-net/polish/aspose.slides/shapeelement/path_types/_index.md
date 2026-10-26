---
title: path_types property
second_title: Aspose.Slides dla Pythona przez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides/shapeelement/path_types/
weight: 40
---
## path_types właściwość
Zwraca tablicę wartości bajtowych określających typ każdego punktu w ścieżce elementu.

**0**  Wskazuje, że punkt jest początkiem figury.

**1**  Wskazuje, że punkt jest jednym z dwóch końcowych punktów linii.

**3**  Wskazuje, że punkt jest końcowym punktem lub punktem kontrolnym sześciennej krzywej Béziera.

**7**  Maskuje wszystkie bity poza trzema najmniej znaczącymi bitami, które określają typ punktu.

**16**  Określa, że odpowiadający segment jest kreskowany.

**32**  Określa, że punkt jest znacznikiem.

**128**  Określa, że punkt jest ostatnim punktem w zamkniętej podścieżce (figura).

**129**  Wskazuje punkt danych, który jest jednocześnie końcowym punktem segmentu linii i ostatnim punktem zamkniętej podścieżki.

### Definicja:
```python
@property
def path_types(self):
    ...
```

### Zobacz także
* klasa [`ShapeElement`](/slides/python-net/pl/aspose.slides/shapeelement)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)