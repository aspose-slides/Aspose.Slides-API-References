---
title: MathDelimiter constructor
second_title: Aspose.Slides dla Pythona przez .NET Referencję API
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathdelimiter/__init__/
weight: 10
---
## __init__(self, element) {#imathelement}
Inicjalizuje MathDelimiter przy podanym elemencie jako jedynym argumentem bazowym

```python
def __init__(self, element):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| element | [`IMathElement`](/slides/python-net/pl/aspose.slides.mathtext/imathelement) | Podstawowy element, do którego stosowany jest delimiter. Może być None. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Rzuca, gdy `element` jest kontenerem dla innych elementów, takich jak MathBlock. W takim przypadku należy wywołać inny konstruktor z argumentem IEnumerable. |

### Zobacz także
* klasa [`IMathElement`](/slides/python-net/pl/aspose.slides.mathtext/imathelement)
* klasa [`MathDelimiter`](/slides/python-net/pl/aspose.slides.mathtext/mathdelimiter)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)