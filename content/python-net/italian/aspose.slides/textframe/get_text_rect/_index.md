---
title: get_text_rect method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/textframe/get_text_rect/
weight: 10
---
## get_text_rect(self) {#}
Restituisce il rettangolo di testo definito dalla geometria della forma genitore.

### Restituisce

Un [`RectangleF`](/slides/python-net/it/aspose.slides/rectanglef) che definisce l'area di testo.



```python
def get_text_rect(self):
    ...
```


### Osservazioni

Le coordinate del rettangolo sono relative all'angolo superiore sinistro della forma genitore.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Il riquadro di testo non è associato a una forma geometrica. |



### Vedi anche
* classe [`TextFrame`](/slides/python-net/it/aspose.slides/textframe)
* classe [`RectangleF`](/slides/python-net/it/aspose.slides/rectanglef)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)