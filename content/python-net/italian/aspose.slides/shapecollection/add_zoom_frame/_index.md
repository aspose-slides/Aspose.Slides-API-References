---
title: add_zoom_frame method
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/shapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Crea un nuovo frame Zoom e lo aggiunge alla fine della raccolta di forme.

### Restituisce

Il nuovo [`IZoomFrame`](/slides/python-net/it/aspose.slides/izoomframe) creato.



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | **float** | La coordinata x del nuovo frame Zoom, in punti. |
| y | **float** | La coordinata y del nuovo frame Zoom, in punti. |
| width | **float** | La larghezza del nuovo frame Zoom, in punti. |
| height | **float** | L'altezza del nuovo frame Zoom, in punti. |
| slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Il [`ISlide`](/slides/python-net/it/aspose.slides/islide) referenziato dal frame Zoom;<br/><br/>            deve appartenere a questa presentazione. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata se la slide referenziata non appartiene alla presentazione corrente. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Crea un nuovo frame Zoom e lo aggiunge alla fine della raccolta di forme.

### Restituisce

Il nuovo [`IZoomFrame`](/slides/python-net/it/aspose.slides/izoomframe) creato.



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | **float** | La coordinata x del nuovo frame Zoom, in punti. |
| y | **float** | La coordinata y del nuovo frame Zoom, in punti. |
| width | **float** | La larghezza del nuovo frame Zoom, in punti. |
| height | **float** | L'altezza del nuovo frame Zoom, in punti. |
| slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Il [`ISlide`](/slides/python-net/it/aspose.slides/islide) referenziato dal frame Zoom;<br/><br/>            deve appartenere a questa presentazione. |
| image | [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage) | L'immagine per la slide referenziata [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage). |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata se la slide referenziata non appartiene alla presentazione corrente. |



### Vedi anche
* classe [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage)
* classe [`ISlide`](/slides/python-net/it/aspose.slides/islide)
* classe [`IZoomFrame`](/slides/python-net/it/aspose.slides/izoomframe)
* classe [`ShapeCollection`](/slides/python-net/it/aspose.slides/shapecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)