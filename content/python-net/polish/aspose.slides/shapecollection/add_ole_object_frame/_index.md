---
title: add_ole_object_frame method
second_title: Aspose.Slides dla Pythona poprzez .NET API
description: 
type: docs
url: /pl/aspose.slides/shapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów.

### Returns

Nowo utworzony [`IOleObjectFrame`](/slides/python-net/pl/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | Współrzędna x nowej ramki OLE, w punktach. |
| y | **float** | Współrzędna y nowej ramki OLE, w punktach. |
| width | **float** | Szerokość nowej ramki OLE, w punktach. |
| height | **float** | Wysokość nowej ramki OLE, w punktach. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/pl/aspose.slides/ioleembeddeddatainfo) | Informacje o osadzonych danych OLE ([`IOleEmbeddedDataInfo`](/slides/python-net/pl/aspose.slides/ioleembeddeddatainfo)). |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów.

### Returns

Nowo utworzony [`IOleObjectFrame`](/slides/python-net/pl/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | Współrzędna x nowej ramki OLE, w punktach. |
| y | **float** | Współrzędna y nowej ramki OLE, w punktach. |
| width | **float** | Szerokość nowej ramki OLE, w punktach. |
| height | **float** | Wysokość nowej ramki OLE, w punktach. |
| class_name | **str** | Nazwa klasy obiektu OLE. |
| path | **str** | Ścieżka do powiązanego pliku. <br/><br/>Ta ścieżka jest przechowywana dosłownie w prezentacji.<br/><br/>Jeśli podano ścieżkę względną, plik będzie niedostępny przy otwieraniu<br/><br/>prezentacji z innego katalogu. |



### See Also
* klasa [`IOleEmbeddedDataInfo`](/slides/python-net/pl/aspose.slides/ioleembeddeddatainfo)
* klasa [`IOleObjectFrame`](/slides/python-net/pl/aspose.slides/ioleobjectframe)
* klasa [`ShapeCollection`](/slides/python-net/pl/aspose.slides/shapecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)