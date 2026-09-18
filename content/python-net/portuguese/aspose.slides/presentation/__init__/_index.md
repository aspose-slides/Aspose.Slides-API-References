---
title: Presentation constructor
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
Este construtor cria uma nova apresentação do zero.
            A apresentação criada tem um slide vazio.

```python
def __init__(self):
    ...
```

## __init__(self, load_options) {#loadoptions}
Este construtor cria uma nova apresentação do zero.
            A apresentação criada tem um slide vazio.

```python
def __init__(self, load_options):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/pt/aspose.slides/loadoptions) | Opções de carregamento adicionais. |

## __init__(self, stream) {#iorawiobase}
Este construtor é o mecanismo principal para ler uma apresentação existente.

```python
def __init__(self, stream):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Fluxo de entrada. |

## __init__(self, file) {#str}
Este construtor recebe um caminho de arquivo de origem do qual o conteúdo da apresentação é lido.

```python
def __init__(self, file):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| file | **str** | Arquivo de entrada. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada quando o arquivo de entrada tem comprimento zero |

## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
Este construtor é o mecanismo principal para ler uma apresentação existente.

```python
def __init__(self, stream, load_options):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Fluxo de entrada. |
| load_options | [`LoadOptions`](/slides/python-net/pt/aspose.slides/loadoptions) | Opções de carregamento adicionais. |

## __init__(self, file, load_options) {#str-loadoptions}
Este construtor recebe um caminho de arquivo de origem do qual o conteúdo da apresentação é lido.

```python
def __init__(self, file, load_options):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| file | **str** | Arquivo de entrada. |
| load_options | [`LoadOptions`](/slides/python-net/pt/aspose.slides/loadoptions) | Opções de carregamento adicionais. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançada quando o arquivo de entrada tem comprimento zero |

### Veja Também
* classe [`LoadOptions`](/slides/python-net/pt/aspose.slides/loadoptions)
* classe [`Presentation`](/slides/python-net/pt/aspose.slides/presentation)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)