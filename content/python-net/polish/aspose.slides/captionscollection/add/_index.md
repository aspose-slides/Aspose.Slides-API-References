---
title: add method
second_title: Aspose.Slides dla Pythona przez .NET API Referencja
description: 
type: docs
url: /pl/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Dodaje napisy zamknięte WebVTT na koniec kolekcji.

### Zwraca

Dodana [`ICaptions`](/slides/python-net/pl/aspose.slides/icaptions) instancja.



```python
def add(self, label, file_path):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| label | **str** | Etykieta napisów zamkniętych. |
| file_path | **str** | Ścieżka do pliku WebVTT. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Rzucany, jeśli `file_path` jest `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, jeśli `file_path` jest pusty. |


## add(self, label, stream) {#str-iorawiobase}
Dodaje napisy zamknięte WebVTT na koniec kolekcji ze strumienia.

### Zwraca

Dodana [`ICaptions`](/slides/python-net/pl/aspose.slides/icaptions) instancja.



```python
def add(self, label, stream):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| label | **str** | Etykieta napisów zamkniętych. |
| stream | **io.RawIOBase** | Strumień wejściowy zawierający dane w formacie WebVTT. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Rzucany, jeśli `stream` jest `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, jeśli dane wejściowe nie są w formacie WebVTT. |



### Zobacz także
* klasa [`CaptionsCollection`](/slides/python-net/pl/aspose.slides/captionscollection)
* klasa [`ICaptions`](/slides/python-net/pl/aspose.slides/icaptions)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)