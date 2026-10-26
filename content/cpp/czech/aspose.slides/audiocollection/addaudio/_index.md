---
title: AddAudio()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Přidá kopii zvukového souboru z jiné prezentace.
type: docs
weight: 53
url: /cs/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) metoda

Přidá kopii zvukového souboru z jiné prezentace.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Zdrojové audio. |

### Návratová hodnota

Přidané audio.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) metoda

Vytvoří a přidá zvuk do prezentace ze streamu.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream, ze kterého se přidá audio. |

### Návratová hodnota

Přidané audio.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metoda

Vytvoří a přidá zvuk do prezentace ze streamu.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream, ze kterého se přidá video audio. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Chování, které bude aplikováno na stream. |

### Návratová hodnota

Přidané audio.

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) metoda

Vytvoří a přidá zvuk do prezentace z pole bajtů.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) bajtů. |

### Návratová hodnota

Přidané audio.

## See Also

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAudio](../../iaudio/)
* Class [AudioCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)