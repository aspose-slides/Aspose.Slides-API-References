---
title: save method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/presentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Salva todos os slides de uma apresentação em um conjunto de arquivos que representam a marcação XAML.


```python
def save(self, options):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/pt/aspose.slides.export.xaml/ixamloptions) | As opções de formato XAML. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Salva todos os slides de uma apresentação em um arquivo com o formato especificado.


```python
def save(self, fname, format):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| fname | **str** | Caminho para o arquivo criado. |
| format | [`SaveFormat`](/slides/python-net/pt/aspose.slides.export/saveformat) | Formato dos dados exportados. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Salva todos os slides de uma apresentação em um stream no formato especificado.


```python
def save(self, stream, format):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream de saída. |
| format | [`SaveFormat`](/slides/python-net/pt/aspose.slides.export/saveformat) | Formato dos dados exportados. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}



```python
def save(self, fname, format, options):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/pt/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/pt/aspose.slides.export/isaveoptions) |  |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Salva todos os slides de uma apresentação em um stream no formato especificado e com opções adicionais.


```python
def save(self, stream, format, options):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream de saída. |
| format | [`SaveFormat`](/slides/python-net/pt/aspose.slides.export/saveformat) | Formato dos dados exportados. |
| options | [`ISaveOptions`](/slides/python-net/pt/aspose.slides.export/isaveoptions) | Opções adicionais de formato. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Se você tentar salvar um arquivo criptografado em <br/>            nenhum formato Office 2007-2010 |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Salva slides especificados de uma apresentação em um arquivo com o formato especificado mantendo o número da página.


```python
def save(self, fname, slides, format):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| fname | **str** | Caminho para o arquivo criado. |
| slides | **List[int]** | Array com posições dos slides, começando em 1. |
| format | [`SaveFormat`](/slides/python-net/pt/aspose.slides.export/saveformat) | Formato dos dados exportados. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Quando o parâmetro stream ou slides for None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Quando o parâmetro slides contém números de página incorretos. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Quando for usado um SaveFormat não suportado, por exemplo PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Salva slides especificados de uma apresentação em um stream no formato especificado mantendo o número da página.


```python
def save(self, stream, slides, format):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream de saída. |
| slides | **List[int]** | Array com posições dos slides, começando em 1. |
| format | [`SaveFormat`](/slides/python-net/pt/aspose.slides.export/saveformat) | Formato dos dados exportados. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Salva slides especificados de uma apresentação em um arquivo com o formato especificado mantendo o número da página.


```python
def save(self, fname, slides, format, options):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| fname | **str** | Caminho para o arquivo criado. |
| slides | **List[int]** | Array com posições dos slides, começando em 1. |
| format | [`SaveFormat`](/slides/python-net/pt/aspose.slides.export/saveformat) | Formato dos dados exportados. |
| options | [`ISaveOptions`](/slides/python-net/pt/aspose.slides.export/isaveoptions) | Opções adicionais de formato. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Salva slides especificados de uma apresentação em um stream no formato especificado mantendo o número da página.


```python
def save(self, stream, slides, format, options):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream de saída. |
| slides | **List[int]** | Array com posições dos slides, começando em 1. |
| format | [`SaveFormat`](/slides/python-net/pt/aspose.slides.export/saveformat) | Formato dos dados exportados. |
| options | [`ISaveOptions`](/slides/python-net/pt/aspose.slides.export/isaveoptions) | Opções adicionais de formato. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Quando o parâmetro stream ou slides for None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Quando o parâmetro slides contém números de página incorretos. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Quando for usado um SaveFormat não suportado, por exemplo PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Veja Também
* classe [`ISaveOptions`](/slides/python-net/pt/aspose.slides.export/isaveoptions)
* classe [`IXamlOptions`](/slides/python-net/pt/aspose.slides.export.xaml/ixamloptions)
* classe [`Presentation`](/slides/python-net/pt/aspose.slides/presentation)
* enumeração [`SaveFormat`](/slides/python-net/pt/aspose.slides.export/saveformat)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)