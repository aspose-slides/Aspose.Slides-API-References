---
title: insert_summary_zoom_frame method
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Crea un nuovo frame Summary Zoom e lo inserisce nella collezione di forme all'indice specificato.

### Restituisce

Il nuovo [`ISummaryZoomFrame`](/slides/python-net/it/aspose.slides/isummaryzoomframe) appena creato.



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice basato su zero in cui inserire il frame Summary Zoom. |
| x | **float** | La coordinata x del nuovo frame Summary Zoom, in punti. |
| y | **float** | La coordinata y del nuovo frame Summary Zoom, in punti. |
| width | **float** | La larghezza del nuovo frame Summary Zoom, in punti. |
| height | **float** | L'altezza del nuovo frame Summary Zoom, in punti. |

### Osservazioni

Questo metodo crea un frame Summary Zoom che aggrega i collegamenti di riepilogo per tutte le sezioni della presentazione.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception) | Lanciata se la presentazione non contiene sezioni, o se la diapositiva di destinazione non appartiene a nessuna sezione. |



### Vedi anche
* classe [`ISummaryZoomFrame`](/slides/python-net/it/aspose.slides/isummaryzoomframe)
* classe [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception)
* classe [`ShapeCollection`](/slides/python-net/it/aspose.slides/shapecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)