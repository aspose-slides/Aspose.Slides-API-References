---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides for C++ API Reference
description: Insert an AudioFrame with embedded audio file. Embedded audio file sound can be a WAV only. It adds new audio into Presentation.Audios list.
type: docs
weight: 261
url: /cpp/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) method


Insert an [AudioFrame](../../audioframe/) with embedded audio file. Embedded audio file sound can be a WAV only. It adds new audio into Presentation.Audios list.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which value should be inserted. |
| x | **float** | X coordinate of a new audio frame. |
| y | **float** | Y coordinate of a new audio frame. |
| width | **float** | Width of a new audio frame. |
| height | **float** | Height of a new audio frame. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Audio](../../audio/) stream. |

### Return Value

Created [AudioFrame](../../audioframe/) object.

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) method


Insert an [AudioFrame](../../audioframe/) with embedded audio file. It uses audio file from Presentation.Audios list.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which value should be inserted. |
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