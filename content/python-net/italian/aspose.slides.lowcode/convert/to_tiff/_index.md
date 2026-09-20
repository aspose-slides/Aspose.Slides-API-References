---
title: to_tiff method
second_title: Riferimento API di Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
Converte la presentazione di input in un set di immagini in formato TIFF.  
  Se il nome del file di output è specificato come "myPath/myFilename.tiff",  
  il risultato verrà salvato come un set di file "myPath/myFilename_N.tiff", dove N è il numero della diapositiva.


```python
@staticmethod
def to_tiff(pres, output_file_name):
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


## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
Converte la presentazione di input in formato TIFF con opzioni personalizzate.  
  Se il nome del file di output è specificato come "myPath/myFilename.tiff" e `multipage` è `false`,  
  il risultato verrà salvato come un set di file "myPath/myFilename_N.tiff", dove N è il numero della diapositiva.  
  Altrimenti, se `multipage` è `true`, il risultato sarà un documento "myPath/myFilename.tiff" a più pagine.


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/it/aspose.slides/presentation) | La presentazione di input. |
| output_file_name | **str** | Il nome del file di output. |
| options | [`ITiffOptions`](/slides/python-net/it/aspose.slides.export/itiffoptions) | Le opzioni di salvataggio TIFF. |
| multipage | **bool** | Specifica se il documento TIFF generato deve essere a più pagine. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### Vedi anche
* classe [`Convert`](/slides/python-net/it/aspose.slides.lowcode/convert)
* classe [`ITiffOptions`](/slides/python-net/it/aspose.slides.export/itiffoptions)
* classe [`Presentation`](/slides/python-net/it/aspose.slides/presentation)
* modulo [`aspose.slides.lowcode`](/slides/python-net/it/aspose.slides.lowcode)
* library [`Aspose.Slides`](/slides/python-net)