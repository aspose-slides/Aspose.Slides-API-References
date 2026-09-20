---
title: add_summary_zoom_frame method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/shapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
Crea un nuovo frame Summary Zoom e lo aggiunge alla fine della raccolta di forme.

### Restituisce

Il [`ISummaryZoomFrame`](/slides/python-net/it/aspose.slides/isummaryzoomframe) appena creato.



```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | **float** | La coordinata x del nuovo frame Summary Zoom, in punti. |
| y | **float** | La coordinata y del nuovo frame Summary Zoom, in punti. |
| width | **float** | La larghezza del nuovo frame Summary Zoom, in punti. |
| height | **float** | L'altezza del nuovo frame Summary Zoom, in punti. |

### Osservazioni

Questo metodo crea un nuovo Summary Zoom e inserisce al suo interno una collezione di oggetti per tutte le sezioni di questa presentazione.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception) | Generata se non ci sono sezioni nella presentazione, o se la diapositiva di destinazione non appartiene a nessuna sezione. |



### Vedi anche
* classe [`ISummaryZoomFrame`](/slides/python-net/it/aspose.slides/isummaryzoomframe)
* classe [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception)
* classe [`ShapeCollection`](/slides/python-net/it/aspose.slides/shapecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)