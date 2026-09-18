---
title: add_video method
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozás alapján
description: 
type: docs
url: /hu/aspose.slides/videocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
Egy videofájl másik prezentációból való másolatát adja hozzá.

### Visszaad

Hozzáadott videó.



```python
def add_video(self, video):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/hu/aspose.slides/ivideo) | Forrásvideó. |


## add_video(self, video_data) {#bytes}
Létrehozza és hozzáadja a videót a prezentációhoz bájttömbből.

### Visszaad

Hozzáadott videó.



```python
def add_video(self, video_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| video_data | **bytes** | Videó bájtok. |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Létrehozza és hozzáadja a videót a prezentációhoz streamből.

### Visszaad

Hozzáadott [`IVideo`](/slides/python-net/hu/aspose.slides/ivideo).



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream, amelyből a videófájlt hozzáadja. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/hu/aspose.slides/loadingstreambehavior) | A viselkedés, amely a streamre lesz alkalmazva. |



### Lásd még
* osztály [`IVideo`](/slides/python-net/hu/aspose.slides/ivideo)
* enumeráció [`LoadingStreamBehavior`](/slides/python-net/hu/aspose.slides/loadingstreambehavior)
* osztály [`VideoCollection`](/slides/python-net/hu/aspose.slides/videocollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)