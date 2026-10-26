---
title: MathDelimiter constructor
second_title: Aspose.Slides pro Python přes .NET API Referenci
description: 
type: docs
url: /cs/aspose.slides.mathtext/mathdelimiter/__init__/
weight: 10
---
## __init__(self, element) {#imathelement}
Inicializuje MathDelimiter s určeným elementem jako jediným základním argumentem


```python
def __init__(self, element):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| element | [`IMathElement`](/slides/python-net/cs/aspose.slides.mathtext/imathelement) | Základní element, na který se delimiter aplikuje. Může být None. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Vyvolá se, pokud je `element` kontejnér pro jiné elementy, například MathBlock. V takovém případě musíte zavolat jiný konstruktor s argumentem IEnumerable. |



### Viz také
* třída [`IMathElement`](/slides/python-net/cs/aspose.slides.mathtext/imathelement)
* třída [`MathDelimiter`](/slides/python-net/cs/aspose.slides.mathtext/mathdelimiter)
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)