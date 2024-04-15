---
title: add_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/add_audio_frame_embedded/
weight: 20
---


## add_audio_frame_embedded {#float-float-float-float-systemiostream}
Adds a new audio frame with embedded audio file to the end of a collection.
            Embedded audio file can be a WAV only.
            It adds new audio into Presentation.Audios list.

### Returns

Created AudioFrame object.



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| audio_stream | System.IO.Stream | Inout stream with audio data. |



## add_audio_frame_embedded {#float-float-float-float-iaudio}
Adds a new audio frame with embedded audio file to the end of a collection.
            It uses audio file from Presentation.Audios list.

### Returns

Created AudioFrame object.



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| audio | IAudio | Audio from Presentation.Audios list. |



### See Also
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
