---
title: add_section_zoom_frame method
second_title: Aspose.Slides dla Pythona poprzez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Tworzy nową ramkę Section Zoom i dodaje ją na koniec kolekcji shape collection.

### Zwraca

Nowo utworzony [`ISectionZoomFrame`](/slides/python-net/pl/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| x | **float** | Współrzędna x nowej ramki Section Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Section Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Section Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Section Zoom, w punktach. |
| section | [`ISection`](/slides/python-net/pl/aspose.slides/isection) | Obiekt [`ISection`](/slides/python-net/pl/aspose.slides/isection) odwoływany przez ramkę Section Zoom; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, jeśli odwoływana sekcja nie należy do bieżącej prezentacji lub nie zawiera slajdów. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Tworzy nową ramkę Section Zoom z określonym obrazem i dodaje ją na koniec kolekcji shape collection.

### Zwraca

Nowo utworzony [`ISectionZoomFrame`](/slides/python-net/pl/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| x | **float** | Współrzędna x nowej ramki Section Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Section Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Section Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Section Zoom, w punktach. |
| section | [`ISection`](/slides/python-net/pl/aspose.slides/isection) | Obiekt [`ISection`](/slides/python-net/pl/aspose.slides/isection) odwoływany przez ramkę Section Zoom; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |
| image | [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage) | Obiekt [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage) wyświetlany w ramce Section Zoom. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, jeśli odwoływana sekcja nie należy do bieżącej prezentacji lub nie zawiera slajdów. |



### Zobacz również
* klasa [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage)
* klasa [`ISection`](/slides/python-net/pl/aspose.slides/isection)
* klasa [`ISectionZoomFrame`](/slides/python-net/pl/aspose.slides/isectionzoomframe)
* klasa [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)