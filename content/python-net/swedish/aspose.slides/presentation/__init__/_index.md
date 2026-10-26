---
title: Presentation constructor
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
Den här konstruktorn skapar en ny presentation från början.
            Skapad presentation har en tom bild.

```python
def __init__(self):
    ...
```

## __init__(self, load_options) {#loadoptions}
Den här konstruktorn skapar en ny presentation från början.
            Skapad presentation har en tom bild.

```python
def __init__(self, load_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/sv/aspose.slides/loadoptions) | Ytterligare inläsningsalternativ. |

## __init__(self, stream) {#iorawiobase}
Den här konstruktorn är den primära mekanismen för att läsa en befintlig Presentation.

```python
def __init__(self, stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | **io.RawIOBase** | Indataström. |

## __init__(self, file) {#str}
Den här konstruktorn får en källfilssökväg från vilken
             innehållet i Presentation läses.

```python
def __init__(self, file):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file | **str** | Indatafil. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när indatafilen har noll längd |

## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
Den här konstruktorn är den primära mekanismen för att läsa en befintlig Presentation.

```python
def __init__(self, stream, load_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | **io.RawIOBase** | Indataström. |
| load_options | [`LoadOptions`](/slides/python-net/sv/aspose.slides/loadoptions) | Ytterligare inläsningsalternativ. |

## __init__(self, file, load_options) {#str-loadoptions}
Den här konstruktorn får en källfilssökväg från vilken
            innehållet i Presentation läses.

```python
def __init__(self, file, load_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file | **str** | Indatafil. |
| load_options | [`LoadOptions`](/slides/python-net/sv/aspose.slides/loadoptions) | Ytterligare inläsningsalternativ. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när indatafilen har noll längd |

### Se även
* klass [`LoadOptions`](/slides/python-net/sv/aspose.slides/loadoptions)
* klass [`Presentation`](/slides/python-net/sv/aspose.slides/presentation)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)