---
title: process method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
Unisce più presentazioni PowerPoint dello stesso formato in un unico file di presentazione.


```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| input_file_names | **List[str]** | Un array dei nomi dei file di presentazione di input. |
| output_file_name | **str** | Il nome del file di output della presentazione unita risultante. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata quando i nomi dei file di input non sono validi o i formati non corrispondono. |


## process(input_file_names, output_stream) {#liststr-iorawiobase}
Unisce più presentazioni PowerPoint dello stesso formato in un unico file di presentazione.


```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| input_file_names | **List[str]** | Un array dei nomi dei file di presentazione di input. |
| output_stream | **io.RawIOBase** | Lo stream di output. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata quando i nomi dei file di input non sono validi o i formati non corrispondono. |


## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
Unisce più presentazioni PowerPoint dello stesso formato in un unico file di presentazione.


```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| input_file_names | **List[str]** | Un array dei nomi dei file di presentazione di input. |
| output_file_name | **str** | Il nome del file di output della presentazione unita risultante. |
| options | [`ISaveOptions`](/slides/python-net/it/aspose.slides.export/isaveoptions) | Le opzioni aggiuntive che definiscono come la presentazione unita viene salvata. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata quando i nomi dei file di input non sono validi o i formati non corrispondono. |


## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
Unisce più presentazioni PowerPoint dello stesso formato in un unico file di presentazione.


```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| input_file_names | **List[str]** | Un array dei nomi dei file di presentazione di input. |
| output_stream | **io.RawIOBase** | Lo stream di output. |
| options | [`ISaveOptions`](/slides/python-net/it/aspose.slides.export/isaveoptions) | Le opzioni aggiuntive che definiscono come la presentazione unita viene salvata. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata quando i nomi dei file di input non sono validi o i formati non corrispondono. |



### Vedi anche
* classe [`ISaveOptions`](/slides/python-net/it/aspose.slides.export/isaveoptions)
* classe [`Merger`](/slides/python-net/it/aspose.slides.lowcode/merger)
* modulo [`aspose.slides.lowcode`](/slides/python-net/it/aspose.slides.lowcode)
* libreria [`Aspose.Slides`](/slides/python-net)