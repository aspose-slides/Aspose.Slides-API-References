---
title: process method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
Mescla várias apresentações PowerPoint do mesmo formato em um único arquivo de apresentação.


```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| input_file_names | **List[str]** | Uma matriz com os nomes dos arquivos de apresentação de entrada. |
| output_file_name | **str** | O nome do arquivo de saída da apresentação mesclada resultante. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançado quando os nomes dos arquivos de entrada são inválidos ou os formatos não correspondem. |


## process(input_file_names, output_stream) {#liststr-iorawiobase}
Mescla várias apresentações PowerPoint do mesmo formato em um único arquivo de apresentação.


```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| input_file_names | **List[str]** | Uma matriz com os nomes dos arquivos de apresentação de entrada. |
| output_stream | **io.RawIOBase** | O fluxo de saída. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançado quando os nomes dos arquivos de entrada são inválidos ou os formatos não correspondem. |


## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
Mescla várias apresentações PowerPoint do mesmo formato em um único arquivo de apresentação.


```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| input_file_names | **List[str]** | Uma matriz com os nomes dos arquivos de apresentação de entrada. |
| output_file_name | **str** | O nome do arquivo de saída da apresentação mesclada resultante. |
| options | [`ISaveOptions`](/slides/python-net/pt/aspose.slides.export/isaveoptions) | As opções adicionais que definem como a apresentação mesclada será salva. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançado quando os nomes dos arquivos de entrada são inválidos ou os formatos não correspondem. |


## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
Mescla várias apresentações PowerPoint do mesmo formato em um único arquivo de apresentação.


```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| input_file_names | **List[str]** | Uma matriz com os nomes dos arquivos de apresentação de entrada. |
| output_stream | **io.RawIOBase** | O fluxo de saída. |
| options | [`ISaveOptions`](/slides/python-net/pt/aspose.slides.export/isaveoptions) | As opções adicionais que definem como a apresentação mesclada será salva. |

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lançado quando os nomes dos arquivos de entrada são inválidos ou os formatos não correspondem. |



### Veja Também
* classe [`ISaveOptions`](/slides/python-net/pt/aspose.slides.export/isaveoptions)
* classe [`Merger`](/slides/python-net/pt/aspose.slides.lowcode/merger)
* módulo [`aspose.slides.lowcode`](/slides/python-net/pt/aspose.slides.lowcode)
* biblioteca [`Aspose.Slides`](/slides/python-net)