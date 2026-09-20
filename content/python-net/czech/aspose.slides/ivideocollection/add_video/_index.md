---
title: add_video method
second_title: Aspose.Slides pro Python prostřednictvím .NET API
description: 
type: docs
url: /cs/aspose.slides/ivideocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
Přidá kopii video souboru z jiné prezentace.

### Návratová hodnota
Přidané video.



```python
def add_video(self, video):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/cs/aspose.slides/ivideo) | Zdrojové video. |


## add_video(self, video_data) {#bytes}
Vytvoří a přidá video do prezentace z pole bajtů.

### Návratová hodnota
Přidané video.



```python
def add_video(self, video_data):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| video_data | **bytes** | Bajty videa. |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Vytvoří a přidá video do prezentace ze streamu.

### Návratová hodnota
Přidané [`IVideo`](/slides/python-net/cs/aspose.slides/ivideo).



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream, ze kterého se přidá video soubor. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/cs/aspose.slides/loadingstreambehavior) | Chování, které bude použito na stream. |



### Viz také
* třída [`IVideo`](/slides/python-net/cs/aspose.slides/ivideo)
* třída [`IVideoCollection`](/slides/python-net/cs/aspose.slides/ivideocollection)
* enumerace [`LoadingStreamBehavior`](/slides/python-net/cs/aspose.slides/loadingstreambehavior)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)