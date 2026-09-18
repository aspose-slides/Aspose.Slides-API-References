---
title: add method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Adiciona legendas fechadas WebVTT ao final da coleção.

### Retorno

A instância [`ICaptions`](/slides/python-net/pt/aspose.slides/icaptions) adicionada.



```python
def add(self, label, file_path):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| label | **str** | O rótulo das legendas fechadas. |
| file_path | **str** | O caminho para o arquivo WebVTT. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lançado se `file_path` for `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Lançado se `file_path` estiver vazio. |


## add(self, label, stream) {#str-iorawiobase}
Adiciona legendas fechadas WebVTT ao final da coleção a partir de um fluxo.

### Retorno

A instância [`ICaptions`](/slides/python-net/pt/aspose.slides/icaptions) adicionada.



```python
def add(self, label, stream):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| label | **str** | O rótulo das legendas fechadas. |
| stream | **io.RawIOBase** | O fluxo de entrada contendo dados no formato WebVTT. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lançado se `stream` for `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Lançado se os dados de entrada não estiverem no formato WebVTT. |



### Veja Também
* classe [`ICaptions`](/slides/python-net/pt/aspose.slides/icaptions)
* classe [`ICaptionsCollection`](/slides/python-net/pt/aspose.slides/icaptionscollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)