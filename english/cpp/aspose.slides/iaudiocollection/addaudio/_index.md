---
title: AddAudio()
second_title: Aspose.Slides for C++ API Reference
description: Adds a copy of an audio file from an another presentation.
type: docs
weight: 14
url: /cpp/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio([System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\>) method


Adds a copy of an audio file from an another presentation.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Source audio. |

### Return Value

Added audio.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudio](../../iaudio/)
* Class [IAudioCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IAudioCollection::AddAudio([System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>) method


Creates and adds a audio to a presentation from stream.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream to add audio from. |

### Return Value

Added audio.

Deprecated
:   Use AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior). The method will be removed in version 17.10.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudio](../../iaudio/)
* Class [Stream](../../../system.io/stream/)
* Class [IAudioCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IAudioCollection::AddAudio([System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>, [LoadingStreamBehavior](../../loadingstreambehavior/)) method


Creates and adds a audio to a presentation from stream.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream to add video audio from. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | The behavior which will be applied to the stream. |

### Return Value

Added audio.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudio](../../iaudio/)
* Class [Stream](../../../system.io/stream/)
* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Class [IAudioCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IAudioCollection::AddAudio([System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>) method


Creates and adds a audio to a presentation from byte array.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) bytes. |

### Return Value

Added audio.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudio](../../iaudio/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAudioCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
