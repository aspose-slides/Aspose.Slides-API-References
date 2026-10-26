---
title: add_zoom_frame method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ishapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Crea un nuovo frame Zoom e lo aggiunge alla fine della collezione di forme.

### Restituisce

Il [`IZoomFrame`](/slides/python-net/it/aspose.slides/izoomframe) appena creato.



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
| slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Il [`ISlide`](/slides/python-net/it/aspose.slides/islide) di riferimento nel frame Zoom; deve appartenere a questa presentazione. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lanciata se la diapositiva di riferimento non appartiene alla presentazione corrente. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Crea un nuovo frame Zoom e lo aggiunge alla fine della collezione di forme.

### Restituisce

Il [`IZoomFrame`](/slides/python-net/it/aspose.slides/izoomframe) appena creato.



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
| slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Il [`ISlide`](/slides/python-net/it/aspose.slides/islide) di riferimento nel frame Zoom; deve appartenere a questa presentazione. |
| image | [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage) | L'immagine per la diapositiva di riferimento [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage). |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lanciata se la diapositiva di riferimento non appartiene alla presentazione corrente. |



### Vedi anche
* classe [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage)
* classe [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection)
* classe [`ISlide`](/slides/python-net/it/aspose.slides/islide)
* classe [`IZoomFrame`](/slides/python-net/it/aspose.slides/izoomframe)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)