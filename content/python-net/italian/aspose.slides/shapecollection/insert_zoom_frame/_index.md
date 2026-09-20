---
title: insert_zoom_frame method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Crea un nuovo frame Zoom e lo inserisce nella collezione di forme all'indice specificato.

### Restituisce

Il [`IZoomFrame`](/slides/python-net/it/aspose.slides/izoomframe) appena creato.



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire il frame Zoom. |
| x | **float** | La coordinata x del nuovo frame Zoom, in punti. |
| y | **float** | La coordinata y del nuovo frame Zoom, in punti. |
| width | **float** | La larghezza del nuovo frame Zoom, in punti. |
| height | **float** | L'altezza del nuovo frame Zoom, in punti. |
| slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Il [`ISlide`](/slides/python-net/it/aspose.slides/islide) referenziato dal frame Zoom. |

### Eccezioni

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata se la diapositiva referenziata non appartiene alla presentazione corrente. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Crea un nuovo frame Zoom con un'immagine predefinita e lo inserisce nella collezione di forme all'indice specificato.

### Restituisce

Il [`IZoomFrame`](/slides/python-net/it/aspose.slides/izoomframe) appena creato.



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire il frame Zoom. |
| x | **float** | La coordinata x del nuovo frame Zoom, in punti. |
| y | **float** | La coordinata y del nuovo frame Zoom, in punti. |
| width | **float** | La larghezza del nuovo frame Zoom, in punti. |
| height | **float** | L'altezza del nuovo frame Zoom, in punti. |
| slide | [`ISlide`](/slides/python-net/it/aspose.slides/islide) | Il [`ISlide`](/slides/python-net/it/aspose.slides/islide) referenziato dal frame Zoom. |
| image | [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage) | L'immagine per la diapositiva referenziata [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage). |

### Eccezioni

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata se la diapositiva referenziata non appartiene alla presentazione corrente. |



### Vedi anche
* classe [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage)
* classe [`ISlide`](/slides/python-net/it/aspose.slides/islide)
* classe [`IZoomFrame`](/slides/python-net/it/aspose.slides/izoomframe)
* classe [`ShapeCollection`](/slides/python-net/it/aspose.slides/shapecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)