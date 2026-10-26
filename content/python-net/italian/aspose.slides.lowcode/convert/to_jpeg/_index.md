---
title: to_jpeg method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
Converte la presentazione di input in un insieme di immagini in formato JPEG.  
            Se il nome del file di output è specificato come "myPath/myFilename.jpeg", 
            il risultato verrà salvato come un insieme di file "myPath/myFilename_N.jpeg", dove N è il numero della diapositiva.


```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/it/aspose.slides/presentation) | La presentazione di input. |
| output_file_name | **str** | Il nome del file di output. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
Converte la presentazione di input in un insieme di immagini in formato JPEG.  
            Se il nome del file di output è specificato come "myPath/myFilename.jpeg", 
            il risultato verrà salvato come un insieme di file "myPath/myFilename_N.jpeg", dove N è il numero della diapositiva.


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/it/aspose.slides/presentation) | La presentazione di input |
| output_file_name | **str** | Il nome del file di output. |
| image_size | [`Size`](/slides/python-net/it/aspose.slides/size) | La dimensione di ogni immagine generata. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Converte la presentazione di input in un insieme di immagini in formato JPEG.  
            Se il nome del file di output è specificato come "myPath/myFilename.jpeg", 
            il risultato verrà salvato come un insieme di file "myPath/myFilename_N.jpeg", dove N è il numero della diapositiva.


```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/it/aspose.slides/presentation) | La presentazione di input. |
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
* classe [`Size`](/slides/python-net/it/aspose.slides/size)
* modulo [`aspose.slides.lowcode`](/slides/python-net/it/aspose.slides.lowcode)
* libreria [`Aspose.Slides`](/slides/python-net)