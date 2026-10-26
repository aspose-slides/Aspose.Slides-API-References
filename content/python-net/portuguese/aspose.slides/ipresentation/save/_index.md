---
title: save method
second_title: Aspose.Slides para Python via API .NET
description: 
type: docs
url: /pt/aspose.slides/ipresentation/save/
weight: 80
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Salva todos os slides de uma apresentação em um conjunto de arquivos que representam marcação XAML.


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
Salva todos os slides de uma apresentação em um fluxo no formato especificado.


```python
def save(self, stream, format):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Fluxo de saída. |
| format | [`SaveFormat`](/slides/python-net/pt/aspose.slides.export/saveformat) | Formato dos dados exportados. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Salva todos os slides de uma apresentação em um arquivo com o formato especificado e com opções adicionais.


```python
def save(self, fname, format, options):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| fname | **str** | Caminho para o arquivo criado. |
| format | [`SaveFormat`](/slides/python-net/pt/aspose.slides.export/saveformat) | Formato dos dados exportados. |
| options | [`ISaveOptions`](/slides/python-net/pt/aspose.slides.export/isaveoptions) | Opções de formato adicionais. |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Salva todos os slides de uma apresentação em um fluxo no formato especificado e com opções adicionais.


```python
def save(self, stream, format, options):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Fluxo de saída. |
| format | [`SaveFormat`](/slides/python-net/pt/aspose.slides.export/saveformat) | Formato dos dados exportados. |
| options | [`ISaveOptions`](/slides/python-net/pt/aspose.slides.export/isaveoptions) | Opções de formato adicionais. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Se você tentar salvar um arquivo criptografado em<br/>            nenhum formato Office 2007-2010 |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Salva slides específicos de uma apresentação em um arquivo com o formato especificado.


```python
def save(self, fname, slides, format):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| fname | **str** | Caminho para o arquivo criado. |
| slides | **List[int]** | Array com as posições dos slides, começando em 1. |
| format | [`SaveFormat`](/slides/python-net/pt/aspose.slides.export/saveformat) | Formato dos dados exportados. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Quando o parâmetro stream ou slides for None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Quando o parâmetro slides contém números de página incorretos. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Quando um SaveFormat não suportado é usado, por exemplo PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Salva slides específicos de uma apresentação em um fluxo no formato especificado.


```python
def save(self, stream, slides, format):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Fluxo de saída. |
| slides | **List[int]** | Array com as posições dos slides, começando em 1. |
| format | [`SaveFormat`](/slides/python-net/pt/aspose.slides.export/saveformat) | Formato dos dados exportados. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Quando o parâmetro stream ou slides for None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Quando o parâmetro slides contém números de página incorretos. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Quando um SaveFormat não suportado é usado, por exemplo PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Salva slides específicos de uma apresentação em um arquivo com o formato especificado.


```python
def save(self, fname, slides, format, options):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| fname | **str** | Caminho para o arquivo criado. |
| slides | **List[int]** | Array com as posições dos slides, começando em 1. |
| format | [`SaveFormat`](/slides/python-net/pt/aspose.slides.export/saveformat) | Formato dos dados exportados. |
| options | [`ISaveOptions`](/slides/python-net/pt/aspose.slides.export/isaveoptions) | Opções de formato adicionais. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Quando o parâmetro stream ou slides for None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Quando o parâmetro slides contém números de página incorretos. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Quando um SaveFormat não suportado é usado, por exemplo PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Salva slides específicos de uma apresentação em um fluxo no formato especificado.


```python
def save(self, stream, slides, format, options):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Fluxo de saída. |
| slides | **List[int]** | Array com as posições dos slides, começando em 1. |
| format | [`SaveFormat`](/slides/python-net/pt/aspose.slides.export/saveformat) | Formato dos dados exportados. |
| options | [`ISaveOptions`](/slides/python-net/pt/aspose.slides.export/isaveoptions) | Opções de formato adicionais. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Quando o parâmetro stream ou slides for None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Quando o parâmetro slides contém números de página incorretos. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Quando um SaveFormat não suportado é usado, por exemplo PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Veja Também
* class [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation)
* class [`ISaveOptions`](/slides/python-net/pt/aspose.slides.export/isaveoptions)
* class [`IXamlOptions`](/slides/python-net/pt/aspose.slides.export.xaml/ixamloptions)
* enumeration [`SaveFormat`](/slides/python-net/pt/aspose.slides.export/saveformat)
* module [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)