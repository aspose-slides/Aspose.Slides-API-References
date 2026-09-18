---
title: insert_clone method
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/ishapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów podanym indeksem.  
            Sklonowany kształt zachowuje pozycję i rozmiar oryginału.

### Zwraca

Nowo utworzony [`IShape`](/slides/python-net/pl/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerowy, pod którym wstawia się sklonowany kształt. |
| source_shape | [`IShape`](/slides/python-net/pl/aspose.slides/ishape) | [`IShape`](/slides/python-net/pl/aspose.slides/ishape) do sklonowania. |


## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów podanym indeksem.  
            Nowy kształt zachowuje szerokość i wysokość `source_shape`.

### Zwraca

Nowo utworzony [`IShape`](/slides/python-net/pl/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerowy, pod którym wstawia się sklonowany kształt. |
| source_shape | [`IShape`](/slides/python-net/pl/aspose.slides/ishape) | [`IShape`](/slides/python-net/pl/aspose.slides/ishape) do sklonowania. |
| x | **float** | Współrzędna x ramki sklonowanego kształtu, w punktach. |
| y | **float** | Współrzędna y ramki sklonowanego kształtu, w punktach. |


## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów podanym indeksem.

### Zwraca

Nowo utworzony [`IShape`](/slides/python-net/pl/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerowy, pod którym wstawia się sklonowany kształt. |
| source_shape | [`IShape`](/slides/python-net/pl/aspose.slides/ishape) | [`IShape`](/slides/python-net/pl/aspose.slides/ishape) do sklonowania. |
| x | **float** | Współrzędna x ramki sklonowanego kształtu, w punktach. |
| y | **float** | Współrzędna y ramki sklonowanego kształtu, w punktach. |
| width | **float** | Szerokość ramki sklonowanego kształtu, w punktach. |
| height | **float** | Wysokość ramki sklonowanego kształtu, w punktach. |

### Zobacz także
* klasa [`IShape`](/slides/python-net/pl/aspose.slides/ishape)
* klasa [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)