---
title: add_section_zoom_frame method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Crea un nuovo frame Section Zoom e lo aggiunge alla fine della collezione di forme.

### Restituisce

Il [`ISectionZoomFrame`](/slides/python-net/it/aspose.slides/isectionzoomframe) appena creato.



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | La coordinata x del nuovo frame Section Zoom, in punti. |
| y | **float** | La coordinata y del nuovo frame Section Zoom, in punti. |
| width | **float** | La larghezza del nuovo frame Section Zoom, in punti. |
| height | **float** | L'altezza del nuovo frame Section Zoom, in punti. |
| section | [`ISection`](/slides/python-net/it/aspose.slides/isection) | Il [`ISection`](/slides/python-net/it/aspose.slides/isection) a cui fa riferimento il frame Section Zoom; <br/><br/>            deve appartenere a questa presentazione e contenere almeno una diapositiva. |

### Eccezioni

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lanciata se la sezione di riferimento non appartiene alla presentazione corrente o non contiene diapositive. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Crea un nuovo frame Section Zoom con un'immagine predefinita e lo aggiunge alla fine della
            collezione di forme.

### Restituisce

Il [`ISectionZoomFrame`](/slides/python-net/it/aspose.slides/isectionzoomframe) appena creato.



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | La coordinata x del nuovo frame Section Zoom, in punti. |
| y | **float** | La coordinata y del nuovo frame Section Zoom, in punti. |
| width | **float** | La larghezza del nuovo frame Section Zoom, in punti. |
| height | **float** | L'altezza del nuovo frame Section Zoom, in punti. |
| section | [`ISection`](/slides/python-net/it/aspose.slides/isection) | Il [`ISection`](/slides/python-net/it/aspose.slides/isection) a cui fa riferimento il frame Section Zoom; <br/><br/>            deve appartenere a questa presentazione e contenere almeno una diapositiva. |
| image | [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage) | Il [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage) da visualizzare all'interno del frame Section Zoom. |

### Eccezioni

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lanciata se la sezione di riferimento non appartiene alla presentazione corrente o non contiene diapositive. |



### Vedi anche
* classe [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage)
* classe [`ISection`](/slides/python-net/it/aspose.slides/isection)
* classe [`ISectionZoomFrame`](/slides/python-net/it/aspose.slides/isectionzoomframe)
* classe [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)