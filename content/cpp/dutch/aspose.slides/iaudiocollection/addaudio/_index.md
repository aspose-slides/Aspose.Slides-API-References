---
title: AddAudio()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een kopie van een audiobestand toe van een andere presentatie.
type: docs
weight: 14
url: /nl/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) methode

Voegt een kopie van een audiobestand toe van een andere presentatie.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Bron-audio. |

### Retourwaarde

Toegevoegde audio.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) methode

Creëert en voegt een audio toe aan een presentatie vanuit een stream.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream om audio toe te voegen. |

### Retourwaarde

Toegevoegde audio.

Verouderd
:   Gebruik AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior). De methode zal worden verwijderd in versie 17.10.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) methode

Creëert en voegt een audio toe aan een presentatie vanuit een stream.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream om video-audio toe te voegen. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Het gedrag dat op de stream wordt toegepast. |

### Retourwaarde

Toegevoegde audio.

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) methode

Creëert en voegt een audio toe aan een presentatie vanuit een byte-array.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) bytes. |

### Retourwaarde

Toegevoegde audio.

## Zie ook

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IAudio](../../iaudio/)
* Klasse [IAudioCollection](../)
* Klasse [Stream](../../../system.io/stream/)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)