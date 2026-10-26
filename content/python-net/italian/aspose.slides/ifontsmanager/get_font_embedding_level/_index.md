---
title: get_font_embedding_level method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ifontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
Determina il livello di incorporamento di un font dal byte array fornito e dal nome del font.

### Valore restituito

Il livello di incorporamento del font specificato.



```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_bytes | **bytes** | Il byte array contenente i dati del font. |
| font_name | **str** | Il nome del font. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Generata quando `font_bytes` è None. |



### Vedi anche
* enumerazione [`EmbeddingLevel`](/slides/python-net/it/aspose.slides/embeddinglevel)
* classe [`IFontsManager`](/slides/python-net/it/aspose.slides/ifontsmanager)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)