---
title: to_png method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
Converte la presentazione in ingresso in un insieme di immagini in formato PNG.  
            Se il nome del file di output è fornito come "myPath/myFilename.png", 
            il risultato verrà salvato come un insieme di file "myPath/myFilename_N.png", dove N è il numero della diapositiva.


```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/it/aspose.slides/presentation) | La presentazione in ingresso. |
| output_file_name | **str** | Il nome del file di output. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
Converte la presentazione in ingresso in un insieme di immagini in formato PNG.  
            Se il nome del file di output è fornito come "myPath/myFilename.png", 
            il risultato verrà salvato come un insieme di file "myPath/myFilename_N.png", dove N è il numero della diapositiva.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/it/aspose.slides/presentation) | La presentazione in ingresso |
| output_file_name | **str** | Il nome del file di output. |
| image_size | **aspose.slides.Size** | La dimensione di ciascuna immagine generata. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Converte la presentazione in ingresso in un insieme di immagini in formato PNG.  
            Se il nome del file di output è fornito come "myPath/myFilename.png", 
            il risultato verrà salvato come un insieme di file "myPath/myFilename_N.png", dove N è il numero della diapositiva.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/it/aspose.slides/presentation) | La presentazione in ingresso. |
| output_file_name | **str** | Il nome del file di output. |
| scale | **float** | Il fattore di scala applicato alle immagini di output rispetto alle dimensioni originali della diapositiva. |
| options | [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions) | Le opzioni di rendering. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Vedi anche
* classe [`Convert`](/slides/python-net/it/aspose.slides.lowcode/convert)
* classe [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions)
* classe [`Presentation`](/slides/python-net/it/aspose.slides/presentation)
* modulo [`aspose.slides.lowcode`](/slides/python-net/it/aspose.slides.lowcode)
* library [`Aspose.Slides`](/slides/python-net)