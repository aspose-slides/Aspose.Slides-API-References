﻿---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---


## insert_audio_frame_embedded {#int-float-float-float-float-iorawiobase}
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
| index | **int** | The zero-based index at which value should be inserted. |
| x | **float** | X coordinate of a new audio frame. |
| y | **float** | Y coordinate of a new audio frame. |
| width | **float** | Width of a new audio frame. |
| height | **float** | Height of a new audio frame. |
| audio_stream | **io.RawIOBase** | Audio stream. |


## insert_audio_frame_embedded {#int-float-float-float-float-iaudio}
Insert an AudioFrame with embedded audio file.
            It uses audio file from Presentation.Audios list.

### Returns

Created AudioFrame object.



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | The zero-based index at which value should be inserted. |
| x | **float** | X coordinate of a new audio frame. |
| y | **float** | Y coordinate of a new audio frame. |
| width | **float** | Width of a new audio frame. |
| height | **float** | Height of a new audio frame. |
| audio | [`IAudio`](/slides/python-net/aspose.slides/iaudio) | Audio from Presentation.Audios list. |



### See Also
* class [`IAudio`](/slides/python-net/aspose.slides/iaudio)
* class [`IAudioFrame`](/slides/python-net/aspose.slides/iaudioframe)
* class [`IShapeCollection`](/slides/python-net/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

