---
title: add_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishapecollection/add_audio_frame_embedded/
weight: 110
---


## add_audio_frame_embedded {#float-float-float-float-System.IO.Stream}
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



## add_audio_frame_embedded {#float-float-float-float-IAudio}
Adds a new audio frame with embedded audio file to the end of a collection.
            Embedded audio file can be a WAV only.
            It adds new audio into Presentation.Audios list.

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
| audio | IAudio |  |



