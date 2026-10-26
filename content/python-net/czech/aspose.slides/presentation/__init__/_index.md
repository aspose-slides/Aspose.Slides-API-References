---
title: Presentation constructor
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
Tento konstruktor vytvoří novou prezentaci od nuly.
            Vytvořená prezentace obsahuje jeden prázdný snímek.

```python
def __init__(self):
    ...
```



## __init__(self, load_options) {#loadoptions}
Tento konstruktor vytvoří novou prezentaci od nuly.
            Vytvořená prezentace obsahuje jeden prázdný snímek.

```python
def __init__(self, load_options):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/cs/aspose.slides/loadoptions) | Další možnosti načítání. |


## __init__(self, stream) {#iorawiobase}
Tento konstruktor je hlavním způsobem čtení existující prezentace.

```python
def __init__(self, stream):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Vstupní proud. |


## __init__(self, file) {#str}
Tento konstruktor získá cestu k zdrojovému souboru, ze kterého jsou načteny údaje prezentace.

```python
def __init__(self, file):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| file | **str** | Vstupní soubor. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvoláno, když má vstupní soubor nulovou délku |


## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
Tento konstruktor je hlavním způsobem čtení existující prezentace.

```python
def __init__(self, stream, load_options):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Vstupní proud. |
| load_options | [`LoadOptions`](/slides/python-net/cs/aspose.slides/loadoptions) | Další možnosti načítání. |


## __init__(self, file, load_options) {#str-loadoptions}
Tento konstruktor získá cestu k zdrojovému souboru, ze kterého jsou načteny údaje prezentace.

```python
def __init__(self, file, load_options):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| file | **str** | Vstupní soubor. |
| load_options | [`LoadOptions`](/slides/python-net/cs/aspose.slides/loadoptions) | Další možnosti načítání. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvoláno, když má vstupní soubor nulovou délku |



### Viz také
* třída [`LoadOptions`](/slides/python-net/cs/aspose.slides/loadoptions)
* třída [`Presentation`](/slides/python-net/cs/aspose.slides/presentation)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)