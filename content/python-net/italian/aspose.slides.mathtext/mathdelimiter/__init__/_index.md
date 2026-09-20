---
title: MathDelimiter constructor
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/mathdelimiter/__init__/
weight: 10
---
## __init__(self, element) {#imathelement}
Inizializza MathDelimiter con element specificato come unico argomento di base


```python
def __init__(self, element):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| element | [`IMathElement`](/slides/python-net/it/aspose.slides.mathtext/imathelement) | L'element base a cui viene applicato il delimitatore. Può essere None. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lancia quando `element` è un contenitore per altri elementi, come MathBlock. In questo caso, è necessario chiamare un costruttore diverso con argomento IEnumerable. |



### Vedi anche
* classe [`IMathElement`](/slides/python-net/it/aspose.slides.mathtext/imathelement)
* classe [`MathDelimiter`](/slides/python-net/it/aspose.slides.mathtext/mathdelimiter)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)