---
title: AddAudio()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en kopia av en ljudfil från en annan presentation.
type: docs
weight: 53
url: /sv/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) metod

Lägger till en kopia av en ljudfil från en annan presentation.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Käll-ljud. |

### Returvärde

Tillagt ljud.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) metod

Skapar och lägger till ett ljud i en presentation från en ström.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ström att lägga till ljud från. |

### Returvärde

Tillagt ljud.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metod

Skapar och lägger till ett ljud i en presentation från en ström.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ström att lägga till video-ljud från. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Beteendet som kommer att tillämpas på strömmen. |

### Returvärde

Tillagt ljud.

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) metod

Skapar och lägger till ett ljud i en presentation från en byte-array.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
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
* Klass [IAudio](../../iaudio/)
* Klass [AudioCollection](../)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)