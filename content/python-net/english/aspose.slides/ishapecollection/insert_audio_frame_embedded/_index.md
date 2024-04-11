---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docS
url: /aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 120
---


## insert_audio_frame_embedded {#int-float-float-float-float-System.IO.Stream}
Insert an AudioFrame with embedded audio file.
            Embedded audio file sound can be a WAV only.
            It adds new audio into Presentation.Audios list.

### Returns

Created AudioFrame object.



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The zero-based index at which value should be inserted. |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| audio_stream | System.IO.Stream | Audio stream. |



## insert_audio_frame_embedded {#int-float-float-float-float-IAudio}
Insert an AudioFrame with embedded audio file.
            Embedded audio file sound can be a WAV only.
            It adds new audio into Presentation.Audios list.

### Returns

Created AudioFrame object.



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The zero-based index at which value should be inserted. |
| x | float | X coordinate of a new audio frame. |
| y | float | Y coordinate of a new audio frame. |
| width | float | Width of a new audio frame. |
| height | float | Height of a new audio frame. |
| audio | IAudio |  |



