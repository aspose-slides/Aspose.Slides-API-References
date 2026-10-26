---
title: MathDelimiter constructor
second_title: Aspose.Slides Python számára a .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides.mathtext/mathdelimiter/__init__/
weight: 10
---
## __init__(self, element) {#imathelement}
Inicializálja a MathDelimiter-t a megadott elemmel, mint egyetlen alapargumentummal


```python
def __init__(self, element):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| element | [`IMathElement`](/slides/python-net/hu/aspose.slides.mathtext/imathelement) | Az az alapelem, amelyre a határoló vonatkozik. Lehet None. |

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | `element` akkor dobja, ha egy másik elem tárolója, például MathBlock. Ebben az esetben egy másik konstruktort kell meghívni `IEnumerable` argumentummal. |


### Lásd még
* osztály [`IMathElement`](/slides/python-net/hu/aspose.slides.mathtext/imathelement)
* osztály [`MathDelimiter`](/slides/python-net/hu/aspose.slides.mathtext/mathdelimiter)
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)