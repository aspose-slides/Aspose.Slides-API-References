---
title: get_font_embedding_level method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/fontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
Determina il livello di incorporamento di un font dal byte array fornito e dal nome del font.

### Returns

Il livello di incorporamento del font specificato.



```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| font_bytes | **bytes** | L'array di byte contenente i dati del font. |
| font_name | **str** | Il nome del font. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Generata quando `font_bytes` è None. |



### See Also
* enumerazione [`EmbeddingLevel`](/slides/python-net/it/aspose.slides/embeddinglevel)
* classe [`FontsManager`](/slides/python-net/it/aspose.slides/fontsmanager)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)