---
title: add_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/shapecollection/add_audio_frame_embedded/
weight: 20
---


## add_audio_frame_embedded {#float-float-float-float-iorawiobase}
Creates a new audio frame with an embedded WAV file and adds it to the end of the
            shape collection. The embedded audio is added to the Presentation.Audios collection.

### Returns

The newly created [`IAudioFrame`](/slides/python-net/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | The x-coordinate of the new audio frame, in points. |
| y | **float** | The y-coordinate of the new audio frame, in points. |
| width | **float** | The width of the new audio frame, in points. |
| height | **float** | The height of the new audio frame, in points. |
| audio_stream | **io.RawIOBase** | An input stream containing WAV audio data to embed. |

### Examples

The following examples shows how to create Audio Frame.


## add_audio_frame_embedded {#float-float-float-float-iaudio}
Creates a new audio frame and adds it to the end of the shape collection using an
            existing audio object from the Presentation.Audios list.

### Returns

The newly created [`IAudioFrame`](/slides/python-net/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | The x-coordinate of the new audio frame, in points. |
| y | **float** | The y-coordinate of the new audio frame, in points. |
| width | **float** | The width of the new audio frame, in points. |
| height | **float** | The height of the new audio frame, in points. |
| audio | [`IAudio`](/slides/python-net/aspose.slides/iaudio) | An [`IAudio`](/slides/python-net/aspose.slides/iaudio) instance from the Presentation.Audios collection. |



### See Also
* class [`IAudio`](/slides/python-net/aspose.slides/iaudio)
* class [`IAudioFrame`](/slides/python-net/aspose.slides/iaudioframe)
* class [`ShapeCollection`](/slides/python-net/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

