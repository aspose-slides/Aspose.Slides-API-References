---
title: insert_section_zoom_frame method
second_title: Aspose.Slides dla Pythona przez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/ishapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Tworzy nową ramkę Section Zoom i wstawia ją do kolekcji kształtów w określonym indeksie.

### Returns

Nowo utworzony [`ISectionZoomFrame`](/slides/python-net/pl/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Indeks zerowy, w którym należy wstawić ramkę Section Zoom. |
| x | **float** | Współrzędna x nowej ramki Section Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Section Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Section Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Section Zoom, w punktach. |
| section | [`ISection`](/slides/python-net/pl/aspose.slides/isection) | [`ISection`](/slides/python-net/pl/aspose.slides/isection) odwołany przez ramkę Section Zoom;<br/><br/> musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, jeśli odwoływana sekcja nie należy do bieżącej prezentacji lub nie zawiera slajdów. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Tworzy nową ramkę Section Zoom z predefiniowanym obrazem i wstawia ją do kolekcji kształtów w określonym indeksie.

### Returns

Nowo utworzony [`ISectionZoomFrame`](/slides/python-net/pl/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Indeks zerowy, w którym należy wstawić ramkę Section Zoom. |
| x | **float** | Współrzędna x nowej ramki Section Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Section Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Section Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Section Zoom, w punktach. |
| section | [`ISection`](/slides/python-net/pl/aspose.slides/isection) | [`ISection`](/slides/python-net/pl/aspose.slides/isection) odwołany przez ramkę Section Zoom;<br/><br/> musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |
| image | [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage) | Obraz wyświetlany w ramce Section Zoom. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, jeśli odwoływana sekcja nie należy do bieżącej prezentacji lub nie zawiera slajdów. |



### See Also
* klasa [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage)
* klasa [`ISection`](/slides/python-net/pl/aspose.slides/isection)
* klasa [`ISectionZoomFrame`](/slides/python-net/pl/aspose.slides/isectionzoomframe)
* klasa [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)