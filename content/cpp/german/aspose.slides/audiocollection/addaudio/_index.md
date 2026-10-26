---
title: AddAudio()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt eine Kopie einer Audiodatei aus einer anderen Präsentation hinzu.
type: docs
weight: 53
url: /de/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) Methode

Fügt eine Kopie einer Audiodatei aus einer anderen Präsentation hinzu.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Quell-Audio. |

### Rückgabewert

Hinzugefügtes Audio.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) Methode

Erstellt und fügt ein Audio zu einer Präsentation aus einem Stream hinzu.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream, aus dem das Audio hinzugefügt wird. |

### Rückgabewert

Hinzugefügtes Audio.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) Methode

Erstellt und fügt ein Audio zu einer Präsentation aus einem Stream hinzu.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream, aus dem das Video-Audio hinzugefügt wird. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Das Verhalten, das auf den Stream angewendet wird. |

### Rückgabewert

Hinzugefügtes Audio.

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) Methode

Erstellt und fügt ein Audio zu einer Präsentation aus einem Byte-Array hinzu.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) Bytes. |

### Rückgabewert

Hinzugefügtes Audio.

## Siehe auch

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAudio](../../iaudio/)
* Class [AudioCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)