---
title: AddAudio()
second_title: Aspose.Slides dla C++ – Referencja API
description: Dodaje kopię pliku audio z innej prezentacji.
type: docs
weight: 14
url: /pl/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) method


Dodaje kopię pliku audio z innej prezentacji.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Źródłowy audio. |

### Wartość zwracana

Dodany dźwięk.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) method


Tworzy i dodaje dźwięk do prezentacji ze strumienia.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień, z którego dodać audio. |

### Wartość zwracana

Dodany dźwięk.

Przestarzałe
:   Użyj AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior). Metoda zostanie usunięta w wersji 17.10.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) method


Tworzy i dodaje dźwięk do prezentacji ze strumienia.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień, z którego dodać audio wideo. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Zachowanie, które zostanie zastosowane do strumienia. |

### Wartość zwracana

Dodany dźwięk.

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) method


Tworzy i dodaje dźwięk do prezentacji z tablicy bajtów.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) bajtów. |

### Wartość zwracana

Dodany dźwięk.

## Zobacz także

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [IAudio](../../iaudio/)
* Klasa [IAudioCollection](../)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)