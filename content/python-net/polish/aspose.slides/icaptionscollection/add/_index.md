---
title: add method
second_title: Aspose.Slides dla Pythona poprzez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/icaptionscollection/add/
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
| label | **str** | Etykieta zamkniętych napisów. |
| file_path | **str** | Ścieżka do pliku WebVTT. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Zgłaszany, jeśli `file_path` jest `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Zgłaszany, jeśli `file_path` jest pusty. |


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
| label | **str** | Etykieta zamkniętych napisów. |
| stream | **io.RawIOBase** | Wejściowy strumień zawierający dane w formacie WebVTT. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Zgłaszany, jeśli `stream` jest `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Zgłaszany, jeśli dane wejściowe nie są w formacie WebVTT. |



### Zobacz także
* klasa [`ICaptions`](/slides/python-net/pl/aspose.slides/icaptions)
* klasa [`ICaptionsCollection`](/slides/python-net/pl/aspose.slides/icaptionscollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)