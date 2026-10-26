---
title: save method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/presentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Salva tutte le diapositive di una presentazione in un insieme di file che rappresentano markup XAML.


```python
def save(self, options):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/it/aspose.slides.export.xaml/ixamloptions) | Le opzioni del formato XAML. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Salva tutte le diapositive di una presentazione in un file con il formato specificato.


```python
def save(self, fname, format):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fname | **str** | Percorso del file creato. |
| format | [`SaveFormat`](/slides/python-net/it/aspose.slides.export/saveformat) | Formato dei dati esportati. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Salva tutte le diapositive di una presentazione in un flusso nel formato specificato.


```python
def save(self, stream, format):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flusso di output. |
| format | [`SaveFormat`](/slides/python-net/it/aspose.slides.export/saveformat) | Formato dei dati esportati. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}



```python
def save(self, fname, format, options):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/it/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/it/aspose.slides.export/isaveoptions) |  |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Salva tutte le diapositive di una presentazione in un flusso nel formato specificato e con opzioni aggiuntive.


```python
def save(self, stream, format, options):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flusso di output. |
| format | [`SaveFormat`](/slides/python-net/it/aspose.slides.export/saveformat) | Formato dei dati esportati. |
| options | [`ISaveOptions`](/slides/python-net/it/aspose.slides.export/isaveoptions) | Opzioni di formato aggiuntive. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Se provi a salvare un file crittografato in <br/>            none Office 2007-2010 format |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Salva le diapositive specificate di una presentazione in un file con il formato specificato mantenendo il numero di pagina.


```python
def save(self, fname, slides, format):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fname | **str** | Percorso del file creato. |
| slides | **List[int]** | Array con le posizioni delle diapositive, a partire da 1. |
| format | [`SaveFormat`](/slides/python-net/it/aspose.slides.export/saveformat) | Formato dei dati esportati. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Quando il parametro stream o slides è None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Quando il parametro slides contiene numeri di pagina errati. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Quando viene utilizzato un SaveFormat non supportato, ad es. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Salva le diapositive specificate di una presentazione in un flusso nel formato specificato mantenendo il numero di pagina.


```python
def save(self, stream, slides, format):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flusso di output. |
| slides | **List[int]** | Array con le posizioni delle diapositive, a partire da 1. |
| format | [`SaveFormat`](/slides/python-net/it/aspose.slides.export/saveformat) | Formato dei dati esportati. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Salva le diapositive specificate di una presentazione in un file con il formato specificato mantenendo il numero di pagina.


```python
def save(self, fname, slides, format, options):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fname | **str** | Percorso del file creato. |
| slides | **List[int]** | Array con le posizioni delle diapositive, a partire da 1. |
| format | [`SaveFormat`](/slides/python-net/it/aspose.slides.export/saveformat) | Formato dei dati esportati. |
| options | [`ISaveOptions`](/slides/python-net/it/aspose.slides.export/isaveoptions) | Opzioni di formato aggiuntive. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Salva le diapositive specificate di una presentazione in un flusso nel formato specificato mantenendo il numero di pagina.


```python
def save(self, stream, slides, format, options):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flusso di output. |
| slides | **List[int]** | Array con le posizioni delle diapositive, a partire da 1. |
| format | [`SaveFormat`](/slides/python-net/it/aspose.slides.export/saveformat) | Formato dei dati esportati. |
| options | [`ISaveOptions`](/slides/python-net/it/aspose.slides.export/isaveoptions) | Opzioni di formato aggiuntive. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Quando il parametro stream o slides è None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Quando il parametro slides contiene numeri di pagina errati. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Quando viene utilizzato un SaveFormat non supportato, ad es. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Vedi anche
* classe [`ISaveOptions`](/slides/python-net/it/aspose.slides.export/isaveoptions)
* classe [`IXamlOptions`](/slides/python-net/it/aspose.slides.export.xaml/ixamloptions)
* classe [`Presentation`](/slides/python-net/it/aspose.slides/presentation)
* enumerazione [`SaveFormat`](/slides/python-net/it/aspose.slides.export/saveformat)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)