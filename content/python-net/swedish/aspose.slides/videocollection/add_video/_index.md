---
title: add_video method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/videocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
Lägger till en kopia av en videofil från en annan presentation.

### Returnerar

Tillagd video.



```python
def add_video(self, video):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/sv/aspose.slides/ivideo) | Källvideo. |


## add_video(self, video_data) {#bytes}
Skapar och lägger till en video i en presentation från en byte-array.

### Returnerar

Tillagd video.



```python
def add_video(self, video_data):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| video_data | **bytes** | Videobytes. |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Skapar och lägger till en video i en presentation från en ström.

### Returnerar

Tillagd [`IVideo`](/slides/python-net/sv/aspose.slides/ivideo).



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | **io.RawIOBase** | Ström att lägga till videofil från. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/sv/aspose.slides/loadingstreambehavior) | Beteendet som kommer att tillämpas på strömmen. |



### Se även
* klass [`IVideo`](/slides/python-net/sv/aspose.slides/ivideo)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/sv/aspose.slides/loadingstreambehavior)
* klass [`VideoCollection`](/slides/python-net/sv/aspose.slides/videocollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)