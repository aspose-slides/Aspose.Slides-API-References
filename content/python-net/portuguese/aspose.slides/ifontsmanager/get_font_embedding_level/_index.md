---
title: get_font_embedding_level method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/ifontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
Determina o nível de incorporação de uma fonte a partir do array de bytes fornecido e do nome da fonte.

### Retorno

O nível de incorporação da fonte especificada.



```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| font_bytes | **bytes** | O array de bytes contendo os dados da fonte. |
| font_name | **str** | O nome da fonte. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lançada quando `font_bytes` é None. |



### Veja Também
* enumeração [`EmbeddingLevel`](/slides/python-net/pt/aspose.slides/embeddinglevel)
* classe [`IFontsManager`](/slides/python-net/pt/aspose.slides/ifontsmanager)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)