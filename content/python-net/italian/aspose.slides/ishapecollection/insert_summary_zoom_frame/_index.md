---
title: insert_summary_zoom_frame method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ishapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Crea un nuovo frame Summary Zoom e lo inserisce nella collezione di forme all'indice specificato.

### Restituisce

Il [`ISummaryZoomFrame`](/slides/python-net/it/aspose.slides/isummaryzoomframe) appena creato.



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire il frame Summary Zoom. |
| x | **float** | La coordinata x del nuovo frame Summary Zoom, in punti. |
| y | **float** | La coordinata y del nuovo frame Summary Zoom, in punti. |
| width | **float** | La larghezza del nuovo frame Summary Zoom, in punti. |
| height | **float** | L'altezza del nuovo frame Summary Zoom, in punti. |

### Osservazioni

Questo metodo crea un frame Summary Zoom che aggrega i collegamenti di riepilogo per tutte le sezioni della presentazione.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception) | Lanciata se la presentazione non contiene sezioni, oppure se la diapositiva di destinazione non appartiene a nessuna sezione. |



### Vedi anche
* classe [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection)
* classe [`ISummaryZoomFrame`](/slides/python-net/it/aspose.slides/isummaryzoomframe)
* classe [`PptxEditException`](/slides/python-net/it/aspose.slides/pptxeditexception)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)