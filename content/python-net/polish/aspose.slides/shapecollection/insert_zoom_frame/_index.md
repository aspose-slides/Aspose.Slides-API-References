---
title: insert_zoom_frame method
second_title: Aspose.Slides dla Pythona – dokumentacja API .NET
description: 
type: docs
url: /pl/aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Tworzy nową ramkę Zoom i wstawia ją do kolekcji kształtów w określonym indeksie.

### Zwraca

Nowo utworzony [`IZoomFrame`](/slides/python-net/pl/aspose.slides/izoomframe).

```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerowy, w którym ma zostać wstawiona ramka Zoom. |
| x | **float** | Współrzędna x nowej ramki Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Zoom, w punktach. |
| slide | [`ISlide`](/slides/python-net/pl/aspose.slides/islide) | Obiekt [`ISlide`](/slides/python-net/pl/aspose.slides/islide) odwołany przez ramkę Zoom. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, jeśli odwołany slajd nie należy do bieżącej prezentacji. |

## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Tworzy nową ramkę Zoom z predefiniowanym obrazem i wstawia ją do kolekcji kształtów w określonym indeksie.

### Zwraca

Nowo utworzony [`IZoomFrame`](/slides/python-net/pl/aspose.slides/izoomframe).

```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerowy, w którym ma zostać wstawiona ramka Zoom. |
| x | **float** | Współrzędna x nowej ramki Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Zoom, w punktach. |
| slide | [`ISlide`](/slides/python-net/pl/aspose.slides/islide) | Obiekt [`ISlide`](/slides/python-net/pl/aspose.slides/islide) odwołany przez ramkę Zoom. |
| image | [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage) | Obraz dla odwołanego slajdu [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage). |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, jeśli odwołany slajd nie należy do bieżącej prezentacji. |

### Zobacz także
* klasa [`IPPImage`](/slides/python-net/pl/aspose.slides/ippimage)
* klasa [`ISlide`](/slides/python-net/pl/aspose.slides/islide)
* klasa [`IZoomFrame`](/slides/python-net/pl/aspose.slides/izoomframe)
* klasa [`ShapeCollection`](/slides/python-net/pl/aspose.slides/shapecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)