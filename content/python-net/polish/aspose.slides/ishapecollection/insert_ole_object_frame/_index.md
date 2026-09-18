---
title: insert_ole_object_frame method
second_title: Aspose.Slides dla Pythona przez .NET API referencja
description: 
type: docs
url: /pl/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów pod wskazanym indeksem.

### Zwraca

Nowo utworzony [`IOleObjectFrame`](/slides/python-net/pl/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks bazujący od zera, pod którym ma zostać wstawiona ramka obiektu OLE. |
| x | **float** | Współrzędna x nowej ramki OLE, w punktach. |
| y | **float** | Współrzędna y nowej ramki OLE, w punktach. |
| width | **float** | Szerokość nowej ramki OLE, w punktach. |
| height | **float** | Wysokość nowej ramki OLE, w punktach. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/pl/aspose.slides/ioleembeddeddatainfo) | Informacje o osadzonych danych OLE ([`IOleEmbeddedDataInfo`](/slides/python-net/pl/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów pod wskazanym indeksem.

### Zwraca

Nowo utworzony [`IOleObjectFrame`](/slides/python-net/pl/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks bazujący od zera, pod którym ma zostać wstawiona ramka obiektu OLE. |
| x | **float** | Współrzędna x nowej ramki OLE, w punktach. |
| y | **float** | Współrzędna y nowej ramki OLE, w punktach. |
| width | **float** | Szerokość nowej ramki OLE, w punktach. |
| height | **float** | Wysokość nowej ramki OLE, w punktach. |
| class_name | **str** | Nazwa klasy obiektu OLE. |
| path | **str** | Ścieżka do powiązanego pliku. <br/><br/>Ta ścieżka jest przechowywana dosłownie w prezentacji.<br/><br/>            Jeśli podano względną ścieżkę, plik będzie niedostępny podczas otwierania<br/><br/>            prezentacji z innego katalogu. |



### Zobacz także
* class [`IOleEmbeddedDataInfo`](/slides/python-net/pl/aspose.slides/ioleembeddeddatainfo)
* class [`IOleObjectFrame`](/slides/python-net/pl/aspose.slides/ioleobjectframe)
* class [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)