---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API Reference
description: Adds a new audio frame with embedded audio file to the end of a collection. Embedded audio file can be a WAV only. It adds new audio into Presentation.Audios list.
type: docs
weight: 248
url: /cpp/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) method


Adds a new audio frame with embedded audio file to the end of a collection. Embedded audio file can be a WAV only. It adds new audio into Presentation.Audios list.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of a new audio frame. |
| y | **float** | Y coordinate of a new audio frame. |
| width | **float** | Width of a new audio frame. |
| height | **float** | Height of a new audio frame. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Inout stream with audio data. |

### Return Value

Created [AudioFrame](../../audioframe/) object.

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) method


Adds a new audio frame with embedded audio file to the end of a collection. It uses audio file from Presentation.Audios list.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | X coordinate of a new audio frame. |
| y | **float** | Y coordinate of a new audio frame. |
| width | **float** | Width of a new audio frame. |
| height | **float** | Height of a new audio frame. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | [Audio](../../audio/) from Presentation.Audios list. |

### Return Value

Created [AudioFrame](../../audioframe/) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [IShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)