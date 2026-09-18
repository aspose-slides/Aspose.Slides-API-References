---
title: add_zoom_frame method
second_title: Aspose.Slides dla Pythona poprzez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides/ishapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Tworzy nową ramkę Zoom i dodaje ją na końcu kolekcji kształtów.

### Zwraca

Nowo utworzony [`IZoomFrame`](/slides/python-net/pl/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| x | **float** | Współrzędna x nowej ramki Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Zoom, w punktach. |
| slide | [`ISlide`](/slides/python-net/pl/aspose.slides/islide) | [`ISlide`](/slides/python-net/pl/aspose.slides/islide) odwoływany przez ramkę Zoom;<br/><br/>            musi należeć do tej prezentacji. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, jeśli odwoływany slajd nie należy do bieżącej prezentacji. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Tworzy nową ramkę Zoom i dodaje ją na końcu kolekcji kształtów.

### Zwraca

Nowo utworzony [`IZoomFrame`](/slides/python-net/pl/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| x | **float** | Współrzędna x nowej ramki Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Zoom, w punktach. |
| slide | [`ISlide`](/slides/python-net/pl/aspose.slides/islide) | [`ISlide`](/slides/python-net/pl/aspose.slides/islide) odwoływany przez ramkę Zoom;<br/><br/>            musi należeć do tej prezentacji. |
| image | [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage) | Obraz dla odwoływanego slajdu [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage). |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, jeśli odwoływany slajd nie należy do bieżącej prezentacji. |



### Zobacz także
* klasa [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage)
* klasa [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection)
* klasa [`ISlide`](/slides/python-net/pl/aspose.slides/islide)
* klasa [`IZoomFrame`](/slides/python-net/pl/aspose.slides/izoomframe)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)