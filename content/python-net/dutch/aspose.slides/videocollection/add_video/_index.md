---
title: add_video method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/videocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
Voegt een kopie van een videobestand toe vanuit een andere presentatie.

### Retourneert

Toegevoegde video.



```python
def add_video(self, video):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/nl/aspose.slides/ivideo) | Bronvideo. |


## add_video(self, video_data) {#bytes}
Maakt een video aan en voegt deze toe aan een presentatie vanuit een byte-array.

### Retourneert

Toegevoegde video.



```python
def add_video(self, video_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| video_data | **bytes** | Video-bytes. |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Maakt een video aan en voegt deze toe aan een presentatie vanuit een stream.

### Retourneert

Toegevoegde [`IVideo`](/slides/python-net/nl/aspose.slides/ivideo).



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream om videobestand van toe te voegen. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/nl/aspose.slides/loadingstreambehavior) | Het gedrag dat op de stream zal worden toegepast. |



### Zie ook
* klasse [`IVideo`](/slides/python-net/nl/aspose.slides/ivideo)
* enumeratie [`LoadingStreamBehavior`](/slides/python-net/nl/aspose.slides/loadingstreambehavior)
* klasse [`VideoCollection`](/slides/python-net/nl/aspose.slides/videocollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)