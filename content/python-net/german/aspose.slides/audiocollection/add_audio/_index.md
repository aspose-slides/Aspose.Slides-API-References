---
title: add_audio method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/audiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
Fügt eine Kopie einer Audiodatei aus einer anderen Präsentation hinzu.

### Rückgabe

Hinzugefügtes Audio.



```python
def add_audio(self, audio):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/de/aspose.slides/iaudio) | Quell-Audio. |


## add_audio(self, stream) {#iorawiobase}
Erstellt und fügt ein Audio aus einem Stream zu einer Präsentation hinzu.

### Rückgabe

Hinzugefügtes Audio.



```python
def add_audio(self, stream):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream, aus dem Audio hinzugefügt wird. |


## add_audio(self, audio_data) {#bytes}
Erstellt und fügt ein Audio aus einem Byte-Array zu einer Präsentation hinzu.

### Rückgabe

Hinzugefügtes Audio.



```python
def add_audio(self, audio_data):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| audio_data | **bytes** | Audio-Bytes. |


## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Erstellt und fügt ein Audio aus einem Stream zu einer Präsentation hinzu.

### Rückgabe

Hinzugefügtes Audio.



```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream, aus dem Video-Audio hinzugefügt wird. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/de/aspose.slides/loadingstreambehavior) | Das Verhalten, das auf den Stream angewendet wird. |



### Siehe auch
* class [`AudioCollection`](/slides/python-net/de/aspose.slides/audiocollection)
* class [`IAudio`](/slides/python-net/de/aspose.slides/iaudio)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/de/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)