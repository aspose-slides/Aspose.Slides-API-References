---
title: Presentation constructor
second_title: Aspose.Slides dla Pythona poprzez .NET – odniesienie do API
description: 
type: docs
url: /pl/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
Ten konstruktor tworzy nową prezentację od podstaw.
            Utworzona prezentacja ma jeden pusty slajd.


```python
def __init__(self):
    ...
```



## __init__(self, load_options) {#loadoptions}
Ten konstruktor tworzy nową prezentację od podstaw.
            Utworzona prezentacja ma jeden pusty slajd.


```python
def __init__(self, load_options):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/pl/aspose.slides/loadoptions) | Dodatkowe opcje ładowania. |


## __init__(self, stream) {#iorawiobase}
Ten konstruktor jest podstawowym mechanizmem odczytu istniejącej Presentation.


```python
def __init__(self, stream):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strumień wejściowy. |


## __init__(self, file) {#str}
Ten konstruktor pobiera ścieżkę pliku źródłowego, z którego
             odczytywana jest zawartość Presentation.


```python
def __init__(self, file):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| file | **str** | Plik wejściowy. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Zgłaszany, gdy plik wejściowy ma zerową długość |


## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
Ten konstruktor jest podstawowym mechanizmem odczytu istniejącej Presentation.


```python
def __init__(self, stream, load_options):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strumień wejściowy. |
| load_options | [`LoadOptions`](/slides/python-net/pl/aspose.slides/loadoptions) | Dodatkowe opcje ładowania. |


## __init__(self, file, load_options) {#str-loadoptions}
Ten konstruktor pobiera ścieżkę pliku źródłowego, z którego
            odczytywana jest zawartość Presentation.


```python
def __init__(self, file, load_options):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| file | **str** | Plik wejściowy. |
| load_options | [`LoadOptions`](/slides/python-net/pl/aspose.slides/loadoptions) | Dodatkowe opcje ładowania. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Zgłaszany, gdy plik wejściowy ma zerową długość |



### Zobacz również
* klasa [`LoadOptions`](/slides/python-net/pl/aspose.slides/loadoptions)
* klasa [`Presentation`](/slides/python-net/pl/aspose.slides/presentation)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)