---
title: add_video method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ivideocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
Fügt eine Kopie einer Videodatei aus einer anderen Präsentation hinzu.

### Rückgabewert

Hinzugefügtes Video.



```python
def add_video(self, video):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/de/aspose.slides/ivideo) | Quellvideo. |


## add_video(self, video_data) {#bytes}
Erstellt und fügt ein Video zu einer Präsentation aus einem Byte-Array hinzu.

### Rückgabewert

Hinzugefügtes Video.



```python
def add_video(self, video_data):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| video_data | **bytes** | Videobytes. |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Erstellt und fügt ein Video zu einer Präsentation aus einem Stream hinzu.

### Rückgabewert

Hinzugefügtes [`IVideo`](/slides/python-net/de/aspose.slides/ivideo).



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream, aus dem die Videodatei hinzugefügt wird. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/de/aspose.slides/loadingstreambehavior) | Das Verhalten, das auf den Stream angewendet wird. |



### Siehe auch
* Klasse [`IVideo`](/slides/python-net/de/aspose.slides/ivideo)
* Klasse [`IVideoCollection`](/slides/python-net/de/aspose.slides/ivideocollection)
* Aufzählung [`LoadingStreamBehavior`](/slides/python-net/de/aspose.slides/loadingstreambehavior)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)