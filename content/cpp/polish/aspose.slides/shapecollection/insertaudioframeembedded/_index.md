---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides dla C++ – referencja API
description: "Tworzy nową ramkę audio z osadzonym plikiem WAV i wstawia ją do kolekcji kształtów pod określonym indeksem. Osadzony dźwięk zostaje dodany do kolekcji Presentation::get_Audios."
type: docs
weight: 300
url: /pl/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metoda

Tworzy nową ramkę audio z osadzonym plikiem WAV i wstawia ją do kolekcji kształtów pod określonym indeksem. Osadzony dźwięk zostaje dodany do kolekcji [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks liczony od zera, pod którym ma zostać wstawiona ramka audio. |
| x | **float** | Współrzędna x nowej ramki audio, w punktach. |
| y | **float** | Współrzędna y nowej ramki audio, w punktach. |
| width | **float** | Szerokość nowej ramki audio, w punktach. |
| height | **float** | Wysokość nowej ramki audio, w punktach. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wejściowy zawierający dane audio WAV do osadzenia. |

### Wartość zwracana

Nowo utworzony [IAudioFrame](../../iaudioframe/).

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) metoda

Tworzy nową ramkę audio i wstawia ją do kolekcji kształtów pod określonym indeksem, używając istniejącego obiektu audio z listy [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks liczony od zera, pod którym ma zostać wstawiona ramka audio. |
| x | **float** | Współrzędna x nowej ramki audio, w punktach. |
| y | **float** | Współrzędna y nowej ramki audio, w punktach. |
| width | **float** | Szerokość nowej ramki audio, w punktach. |
| height | **float** | Wysokość nowej ramki audio, w punktach. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Instancja [IAudio](../../iaudio/) z kolekcji [Presentation::get_Audios](../../presentation/get_audios/) do osadzenia. |

### Wartość zwracana

Nowo utworzony [IAudioFrame](../../iaudioframe/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAudioFrame](../../iaudioframe/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [ShapeCollection](../)
* Klasa [IAudio](../../iaudio/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)