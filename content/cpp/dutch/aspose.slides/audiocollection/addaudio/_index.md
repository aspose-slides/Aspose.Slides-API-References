---
title: AddAudio()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een kopie van een audiobestand toe van een andere presentatie.
type: docs
weight: 53
url: /nl/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) methode

Voegt een kopie van een audiobestand toe van een andere presentatie.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Bron-audio. |

### Retourwaarde

Audio toegevoegd.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) methode

Maakt en voegt een audio toe aan een presentatie vanuit een stream.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream waaruit audio wordt toegevoegd. |

### Retourwaarde

Audio toegevoegd.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) methode

Maakt en voegt een audio toe aan een presentatie vanuit een stream.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream waaruit video-audio wordt toegevoegd. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Het gedrag dat op de stream zal worden toegepast. |

### Retourwaarde

Audio toegevoegd.

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) methode

Maakt en voegt een audio toe aan een presentatie vanuit een byte-array.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) bytes. |

### Retourwaarde

Audio toegevoegd.

## Zie ook

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAudio](../../iaudio/)
* Class [AudioCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)