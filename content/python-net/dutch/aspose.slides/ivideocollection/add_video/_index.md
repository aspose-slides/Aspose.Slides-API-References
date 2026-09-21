---
title: add_video method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ivideocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
Voegt een kopie van een videobestand toe van een andere presentatie.

### Retour

Video toegevoegd.



```python
def add_video(self, video):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/nl/aspose.slides/ivideo) | Bronvideo. |


## add_video(self, video_data) {#bytes}
Maakt een video aan en voegt deze toe aan een presentatie vanuit een byte-array.

### Retour

Video toegevoegd.



```python
def add_video(self, video_data):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| video_data | **bytes** | Video-bytes. |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Maakt een video aan en voegt deze toe aan een presentatie vanuit een stream.

### Retour

Toegevoegde [`IVideo`](/slides/python-net/nl/aspose.slides/ivideo).



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream waaruit het videobestand wordt toegevoegd. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/nl/aspose.slides/loadingstreambehavior) | Het gedrag dat op de stream wordt toegepast. |



### Zie ook
* klasse [`IVideo`](/slides/python-net/nl/aspose.slides/ivideo)
* klasse [`IVideoCollection`](/slides/python-net/nl/aspose.slides/ivideocollection)
* enumeratie [`LoadingStreamBehavior`](/slides/python-net/nl/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)