---
title: AddAudio()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Dodaje kopię pliku audio z innej prezentacji.
type: docs
weight: 53
url: /pl/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) metoda


Dodaje kopię pliku audio z innej prezentacji.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Źródłowy plik audio. |

### Wartość zwracana

Dodane audio.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) metoda


Tworzy i dodaje dźwięk do prezentacji ze strumienia.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień, z którego dodać audio. |

### Wartość zwracana

Dodane audio.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metoda


Tworzy i dodaje dźwięk do prezentacji ze strumienia.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień, z którego dodać audio wideo. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Zachowanie, które zostanie zastosowane do strumienia. |

### Wartość zwracana

Dodane audio.

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) metoda


Tworzy i dodaje dźwięk do prezentacji z tablicy bajtów.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) bajtów. |

### Wartość zwracana

Dodane audio.

## Zobacz także

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [IAudio](../../iaudio/)
* Klasa [AudioCollection](../)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)