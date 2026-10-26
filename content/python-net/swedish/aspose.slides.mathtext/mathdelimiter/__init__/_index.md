---
title: MathDelimiter constructor
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathdelimiter/__init__/
weight: 10
---
## __init__(self, element) {#imathelement}
Initierar MathDelimiter med det angivna elementet som enda basargument


```python
def __init__(self, element):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| element | [`IMathElement`](/slides/python-net/sv/aspose.slides.mathtext/imathelement) | Bas-elementet som avgränsaren appliceras på. Kan vara None. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kastas när `element` är en behållare för andra element, såsom MathBlock. I så fall måste du anropa en annan konstruktor med IEnumerable-argument. |



### Se även
* klass [`IMathElement`](/slides/python-net/sv/aspose.slides.mathtext/imathelement)
* klass [`MathDelimiter`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)