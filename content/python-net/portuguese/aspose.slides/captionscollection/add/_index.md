---
title: add method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Adiciona legendas closed captions em WebVTT ao final da coleção.

### Retorno

A instância [`ICaptions`](/slides/python-net/pt/aspose.slides/icaptions) adicionada.



```python
def add(self, label, file_path):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| label | **str** | O rótulo das legendas closed captions. |
| file_path | **str** | O caminho para o arquivo WebVTT. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lançada se `file_path` for `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada se `file_path` estiver vazio. |


## add(self, label, stream) {#str-iorawiobase}
Adiciona legendas closed captions em WebVTT ao final da coleção a partir de um fluxo.

### Retorno

A instância [`ICaptions`](/slides/python-net/pt/aspose.slides/icaptions) adicionada.



```python
def add(self, label, stream):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| label | **str** | O rótulo das legendas closed captions. |
| stream | **io.RawIOBase** | O fluxo de entrada contendo dados no formato WebVTT. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lançada se `stream` for `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada se os dados de entrada não estiverem no formato WebVTT. |



### Veja também
* classe [`CaptionsCollection`](/slides/python-net/pt/aspose.slides/captionscollection)
* classe [`ICaptions`](/slides/python-net/pt/aspose.slides/icaptions)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)