---
title: Presentation constructor
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
Dieser Konstruktor erstellt eine neue Präsentation von Grund auf.
Erstellte Präsentation enthält eine leere Folie.

```python
def __init__(self):
    ...
```

## __init__(self, load_options) {#loadoptions}
Dieser Konstruktor erstellt eine neue Präsentation von Grund auf.
Erstellte Präsentation enthält eine leere Folie.

```python
def __init__(self, load_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/de/aspose.slides/loadoptions) | Zusätzliche Ladeoptionen. |

## __init__(self, stream) {#iorawiobase}
Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer bestehenden Präsentation.

```python
def __init__(self, stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Eingabestream. |

## __init__(self, file) {#str}
Dieser Konstruktor erhält einen Quellpfad, von dem der Inhalt der Präsentation gelesen wird.

```python
def __init__(self, file):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file | **str** | Eingabedatei. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die Eingabedatei die Länge 0 hat |

## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer bestehenden Präsentation.

```python
def __init__(self, stream, load_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Eingabestream. |
| load_options | [`LoadOptions`](/slides/python-net/de/aspose.slides/loadoptions) | Zusätzliche Ladeoptionen. |

## __init__(self, file, load_options) {#str-loadoptions}
Dieser Konstruktor erhält einen Quellpfad, von dem der Inhalt der Präsentation gelesen wird.

```python
def __init__(self, file, load_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file | **str** | Eingabedatei. |
| load_options | [`LoadOptions`](/slides/python-net/de/aspose.slides/loadoptions) | Zusätzliche Ladeoptionen. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die Eingabedatei die Länge 0 hat |

### Siehe auch
* Klasse [`LoadOptions`](/slides/python-net/de/aspose.slides/loadoptions)
* Klasse [`Presentation`](/slides/python-net/de/aspose.slides/presentation)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)