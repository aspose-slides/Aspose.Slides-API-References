---
title: AddAudio()
second_title: Aspose.Slides for C++ API Reference
description: Adds a copy of an audio file from an another presentation.
type: docs
weight: 14
url: /aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) method


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

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) method


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

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) method


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

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) method


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

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAudio](../../iaudio/)
* Class [IAudioCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)