---
title: MathDelimiter constructor
second_title: Aspose.Slides für Python über .NET API Reference
description: 
type: docs
url: /de/aspose.slides.mathtext/mathdelimiter/__init__/
weight: 10
---
## __init__(self, element) {#imathelement}
Initialisiert MathDelimiter mit dem angegebenen element als einziges Basisargument

```python
def __init__(self, element):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| element | [`IMathElement`](/slides/python-net/de/aspose.slides.mathtext/imathelement) | Das Basiselement, auf das der Delimiter angewendet wird. Kann None sein. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wird ausgelöst, wenn `element` ein Container für andere Elemente ist, wie z.B. MathBlock. In diesem Fall muss ein anderer Konstruktor mit IEnumerable-Argument aufgerufen werden. |

### Siehe auch
* Klasse [`IMathElement`](/slides/python-net/de/aspose.slides.mathtext/imathelement)
* Klasse [`MathDelimiter`](/slides/python-net/de/aspose.slides.mathtext/mathdelimiter)
* Modul [`aspose.slides.mathtext`](/slides/python-net/de/aspose.slides.mathtext)
* Bibliothek [`Aspose.Slides`](/slides/python-net)