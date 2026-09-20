---
title: insert_section_zoom_frame method
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Crea un nuovo frame Section Zoom e lo inserisce nella raccolta di forme all'indice specificato.

### Restituisce

Il nuovo [`ISectionZoomFrame`](/slides/python-net/it/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire il frame Section Zoom. |
| x | **float** | La coordinata x del nuovo frame Section Zoom, in punti. |
| y | **float** | La coordinata y del nuovo frame Section Zoom, in punti. |
| width | **float** | La larghezza del nuovo frame Section Zoom, in punti. |
| height | **float** | L'altezza del nuovo frame Section Zoom, in punti. |
| section | [`ISection`](/slides/python-net/it/aspose.slides/isection) | Il [`ISection`](/slides/python-net/it/aspose.slides/isection) referenziato dal frame Section Zoom;<br/><br/>            deve appartenere a questa presentazione e contenere almeno una diapositiva. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata se la sezione referenziata non appartiene alla presentazione corrente o non contiene diapositive. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Crea un nuovo frame Section Zoom con un'immagine predefinita e lo inserisce nella raccolta di forme all'indice specificato.

### Restituisce

Il nuovo [`ISectionZoomFrame`](/slides/python-net/it/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire il frame Section Zoom. |
| x | **float** | La coordinata x del nuovo frame Section Zoom, in punti. |
| y | **float** | La coordinata y del nuovo frame Section Zoom, in punti. |
| width | **float** | La larghezza del nuovo frame Section Zoom, in punti. |
| height | **float** | L'altezza del nuovo frame Section Zoom, in punti. |
| section | [`ISection`](/slides/python-net/it/aspose.slides/isection) | Il [`ISection`](/slides/python-net/it/aspose.slides/isection) referenziato dal frame Section Zoom;<br/><br/>            deve appartenere a questa presentazione e contenere almeno una diapositiva. |
| image | [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage) | L'immagine da visualizzare all'interno del frame Section Zoom. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata se la sezione referenziata non appartiene alla presentazione corrente o non contiene diapositive. |



### Vedi anche
* classe [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage)
* classe [`ISection`](/slides/python-net/it/aspose.slides/isection)
* classe [`ISectionZoomFrame`](/slides/python-net/it/aspose.slides/isectionzoomframe)
* classe [`ShapeCollection`](/slides/python-net/it/aspose.slides/shapecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)