---
title: AddAudio()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Přidá kopii zvukového souboru z jiné prezentace.
type: docs
weight: 14
url: /cs/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) metoda


Přidá kopii zvukového souboru z jiné prezentace.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Zdrojové audio. |

### Návratová hodnota

Přidané audio.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) metoda


Vytvoří a přidá audio do prezentace ze streamu.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream, ze kterého se přidá audio. |

### Návratová hodnota

Přidané audio.

Zastaralé
:   Použijte AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior). Metoda bude odstraněna ve verzi 17.10.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metoda


Vytvoří a přidá audio do prezentace ze streamu.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream, ze kterého se přidá video audio. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Chování, které bude použito na stream. |

### Návratová hodnota

Přidané audio.

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) metoda


Vytvoří a přidá audio do prezentace z pole bajtů.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) bajtů. |

### Návratová hodnota

Přidané audio.

## See Also

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAudio](../../iaudio/)
* Class [IAudioCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)