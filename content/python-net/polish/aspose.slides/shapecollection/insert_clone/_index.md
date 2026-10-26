---
title: insert_clone method
second_title: Aspose.Slides dla Pythona – referencja API .NET
description: 
type: docs
url: /pl/aspose.slides/shapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów pod wskazanym indeksem.
            Sklonowany kształt zachowuje pozycję i rozmiar oryginału.

### Zwraca

Nowo utworzony [`IShape`](/slides/python-net/pl/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerowy, w którym należy wstawić sklonowany kształt. |
| source_shape | [`IShape`](/slides/python-net/pl/aspose.slides/ishape) | Obiekt [`IShape`](/slides/python-net/pl/aspose.slides/ishape) do sklonowania. |


## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów pod wskazanym indeksem.
            Nowy kształt zachowuje szerokość i wysokość `source_shape`.

### Zwraca

Nowo utworzony [`IShape`](/slides/python-net/pl/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerowy, w którym należy wstawić sklonowany kształt. |
| source_shape | [`IShape`](/slides/python-net/pl/aspose.slides/ishape) | Obiekt [`IShape`](/slides/python-net/pl/aspose.slides/ishape) do sklonowania. |
| x | **float** | Współrzędna x ramki sklonowanego kształtu, w punktach. |
| y | **float** | Współrzędna y ramki sklonowanego kształtu, w punktach. |


## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów pod wskazanym indeksem.

### Zwraca

Nowo utworzony [`IShape`](/slides/python-net/pl/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerowy, w którym należy wstawić sklonowany kształt. |
| source_shape | [`IShape`](/slides/python-net/pl/aspose.slides/ishape) | Obiekt [`IShape`](/slides/python-net/pl/aspose.slides/ishape) do sklonowania. |
| x | **float** | Współrzędna x ramki sklonowanego kształtu, w punktach. |
| y | **float** | Współrzędna y ramki sklonowanego kształtu, w punktach. |
| width | **float** | Szerokość ramki sklonowanego kształtu, w punktach. |
| height | **float** | Wysokość ramki sklonowanego kształtu, w punktach. |



### Zobacz także
* klasa [`IShape`](/slides/python-net/pl/aspose.slides/ishape)
* klasa [`ShapeCollection`](/slides/python-net/pl/aspose.slides/shapecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)