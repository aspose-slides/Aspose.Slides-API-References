---
title: Presentation constructor
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
Ez a konstruktor egy új prezentációt hoz létre a semmiből.
            A létrehozott prezentációnak egy üres diája van.


```python
def __init__(self):
    ...
```



## __init__(self, load_options) {#loadoptions}
Ez a konstruktor egy új prezentációt hoz létre a semmiből.
            A létrehozott prezentációnak egy üres diája van.


```python
def __init__(self, load_options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/hu/aspose.slides/loadoptions) | További load_options. |


## __init__(self, stream) {#iorawiobase}
Ez a konstruktor az elsődleges mechanizmus egy meglévő Presentation olvasásához.


```python
def __init__(self, stream):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Bemeneti stream. |


## __init__(self, file) {#str}
Ez a konstruktor egy forrás file útvonalat ad meg, amelyről a Presentation tartalma beolvasásra kerül.


```python
def __init__(self, file):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| file | **str** | Bemeneti file. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel akkor keletkezik, ha az input file hossza nulla |


## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
Ez a konstruktor az elsődleges mechanizmus egy meglévő Presentation olvasásához.


```python
def __init__(self, stream, load_options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Bemeneti stream. |
| load_options | [`LoadOptions`](/slides/python-net/hu/aspose.slides/loadoptions) | További load_options. |


## __init__(self, file, load_options) {#str-loadoptions}
Ez a konstruktor egy forrás file útvonalat ad meg, amelyről a Presentation tartalma beolvasásra kerül.


```python
def __init__(self, file, load_options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| file | **str** | Bemeneti file. |
| load_options | [`LoadOptions`](/slides/python-net/hu/aspose.slides/loadoptions) | További load_options. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel akkor keletkezik, ha az input file hossza nulla |



### Lásd még
* osztály [`LoadOptions`](/slides/python-net/hu/aspose.slides/loadoptions)
* osztály [`Presentation`](/slides/python-net/hu/aspose.slides/presentation)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)