---
title: add_video method
second_title: Aspose.Slides dla Pythona via .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/videocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
Dodaje kopię pliku wideo z innej prezentacji.

### Zwraca

Dodany plik wideo.



```python
def add_video(self, video):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/pl/aspose.slides/ivideo) | Wideo źródłowe. |


## add_video(self, video_data) {#bytes}
Tworzy i dodaje wideo do prezentacji z tablicy bajtów.

### Zwraca

Dodany plik wideo.



```python
def add_video(self, video_data):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| video_data | **bytes** | Bajty wideo. |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Tworzy i dodaje wideo do prezentacji ze strumienia.

### Zwraca

Dodany [`IVideo`](/slides/python-net/pl/aspose.slides/ivideo).



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strumień, z którego dodać plik wideo. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/pl/aspose.slides/loadingstreambehavior) | Zachowanie, które zostanie zastosowane do strumienia. |



### Zobacz też
* klasa [`IVideo`](/slides/python-net/pl/aspose.slides/ivideo)
* enumeracja [`LoadingStreamBehavior`](/slides/python-net/pl/aspose.slides/loadingstreambehavior)
* klasa [`VideoCollection`](/slides/python-net/pl/aspose.slides/videocollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)