---
title: AddAudio()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt eine Kopie einer Audiodatei aus einer anderen Präsentation hinzu.
type: docs
weight: 14
url: /de/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) method

Fügt eine Kopie einer Audiodatei aus einer anderen Präsentation hinzu.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Source audio. |

### Rückgabewert

Hinzugefügtes Audio.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) method

Erstellt und fügt ein Audio zu einer Präsentation aus einem Stream hinzu.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream to add audio from. |

### Rückgabewert

Hinzugefügtes Audio.

Veraltet
:   Verwenden Sie AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior). Die Methode wird in Version 17.10 entfernt.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) method

Erstellt und fügt ein Audio zu einer Präsentation aus einem Stream hinzu.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream, aus dem das Video-Audio hinzugefügt wird. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Das Verhalten, das auf den Stream angewendet wird. |

### Rückgabewert

Hinzugefügtes Audio.

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) method

Erstellt und fügt ein Audio zu einer Präsentation aus einem Byte-Array hinzu.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) Bytes. |

### Rückgabewert

Hinzugefügtes Audio.

## Siehe auch

* Aufzählung [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IAudio](../../iaudio/)
* Klasse [IAudioCollection](../)
* Klasse [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)