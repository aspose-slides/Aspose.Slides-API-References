---
title: insert_zoom_frame method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Crea un nuovo fotogramma Zoom e lo inserisce nella collezione di forme all'indice specificato.

### Restituisce

Il nuovo [`IZoomFrame`](/slides/python-net/it/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire il fotogramma Zoom. |
| x | **float** | La coordinata x del nuovo fotogramma Zoom, in punti. |
| y | **float** | La coordinata y del nuovo fotogramma Zoom, in punti. |
| width | **float** | La larghezza del nuovo fotogramma Zoom, in punti. |
| height | **float** | L'altezza del nuovo fotogramma Zoom, in punti. |
| slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Il [`ISlide`](/slides/python-net/it/aspose.slides/islide) a cui fa riferimento il fotogramma Zoom. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lanciata se la diapositiva di riferimento non appartiene alla presentazione corrente. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Crea un nuovo fotogramma Zoom con un'immagine predefinita e lo inserisce nella collezione di forme
            all'indice specificato.

### Restituisce

Il nuovo [`IZoomFrame`](/slides/python-net/it/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire il fotogramma Zoom. |
| x | **float** | La coordinata x del nuovo fotogramma Zoom, in punti. |
| y | **float** | La coordinata y del nuovo fotogramma Zoom, in punti. |
| width | **float** | La larghezza del nuovo fotogramma Zoom, in punti. |
| height | **float** | L'altezza del nuovo fotogramma Zoom, in punti. |
| slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Il [`ISlide`](/slides/python-net/it/aspose.slides/islide) a cui fa riferimento il fotogramma Zoom. |
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