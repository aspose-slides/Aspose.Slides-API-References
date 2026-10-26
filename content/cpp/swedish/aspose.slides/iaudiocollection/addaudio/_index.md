---
title: AddAudio()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en kopia av en ljudfil från en annan presentation.
type: docs
weight: 14
url: /sv/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) metod


Lägger till en kopia av en ljudfil från en annan presentation.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Source audio. |

### Returvärde

Tillagt ljud.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) metod


Skapar och lägger till ett ljud i en presentation från en ström.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ström att lägga till ljud från. |

### Returvärde

Tillagt ljud.

Föråldrad:
   Använd AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior). Metoden kommer att tas bort i version 17.10.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metod


Skapar och lägger till ett ljud i en presentation från en ström.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ström att lägga till video-ljud från. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Beteendet som kommer att tillämpas på strömmen. |

### Returvärde

Tillagt ljud.

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) metod


Skapar och lägger till ett ljud i en presentation från en byte-array.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) byte. |

### Returvärde

Tillagt ljud.

## Se även

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAudio](../../iaudio/)
* Class [IAudioCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)