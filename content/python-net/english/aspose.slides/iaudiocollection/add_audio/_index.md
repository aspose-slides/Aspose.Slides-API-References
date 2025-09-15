---
title: add_audio method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/iaudiocollection/add_audio/
weight: 10
---


## add_audio {#iaudio}
Adds a copy of an audio file from an another presentation.

### Returns

Added audio.



```python
def add_audio(self, audio):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/aspose.slides/iaudio) | Source audio. |


## add_audio {#iorawiobase}
Creates and adds a audio to a presentation from stream.

### Returns

Added audio.



```python
def add_audio(self, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream to add audio from. |


## add_audio {#bytes}
Creates and adds a audio to a presentation from byte array.

### Returns

Added audio.



```python
def add_audio(self, audio_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| audio_data | **bytes** | Audio bytes. |


## add_audio {#iorawiobase-loadingstreambehavior}
Creates and adds a audio to a presentation from stream.

### Returns

Added audio.



```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream to add video audio from. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/aspose.slides/loadingstreambehavior) | The behavior which will be applied to the stream. |



### See Also
* class [`IAudio`](/slides/python-net/aspose.slides/iaudio)
* class [`IAudioCollection`](/slides/python-net/aspose.slides/iaudiocollection)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

