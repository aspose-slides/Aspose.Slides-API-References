---
title: insert_section_zoom_frame method
second_title: Aspose.Slides dla Pythona przez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Tworzy nową ramkę Section Zoom i wstawia ją do kolekcji kształtów w określonym indeksie.

### Zwraca

Nowo utworzony [`ISectionZoomFrame`](/slides/python-net/pl/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerobazowy, w którym wstawia się ramkę Section Zoom. |
| x | **float** | Współrzędna x nowej ramki Section Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Section Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Section Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Section Zoom, w punktach. |
| section | [`ISection`](/slides/python-net/pl/aspose.slides/isection) | [`ISection`](/slides/python-net/pl/aspose.slides/isection) odwoływany przez ramkę Section Zoom;<br/><br/>            musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, jeśli odwoływana sekcja nie należy do bieżącej prezentacji lub nie zawiera slajdów. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Tworzy nową ramkę Section Zoom z predefiniowanym obrazem i wstawia ją do kolekcji kształtów w określonym indeksie.

### Zwraca

Nowo utworzony [`ISectionZoomFrame`](/slides/python-net/pl/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerobazowy, w którym wstawia się ramkę Section Zoom. |
| x | **float** | Współrzędna x nowej ramki Section Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Section Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Section Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Section Zoom, w punktach. |
| section | [`ISection`](/slides/python-net/pl/aspose.slides/isection) | [`ISection`](/slides/python-net/pl/aspose.slides/isection) odwoływany przez ramkę Section Zoom;<br/><br/>            musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |
| image | [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage) | Obraz wyświetlany wewnątrz ramki Section Zoom. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, jeśli odwoływana sekcja nie należy do bieżącej prezentacji lub nie zawiera slajdów. |



### Zobacz także
* klasa [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage)
* klasa [`ISection`](/slides/python-net/pl/aspose.slides/isection)
* klasa [`ISectionZoomFrame`](/slides/python-net/pl/aspose.slides/isectionzoomframe)
* klasa [`ShapeCollection`](/slides/python-net/pl/aspose.slides/shapecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)