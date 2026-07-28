---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides dla C++ Referencja API
description: Tworzy nową ramkę audio z osadzonym plikiem WAV i wstawia ją do kolekcji kształtów pod wskazanym indeksem. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios.
type: docs
weight: 261
url: /pl/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metoda

Tworzy nową ramkę audio z osadzonym plikiem WAV i wstawia ją do kolekcji kształtów pod wskazanym indeksem. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks rozpoczynający od zera, w którym należy wstawić ramkę audio. |
| x | **float** | Współrzędna x nowej ramki audio, w punktach. |
| y | **float** | Współrzędna y nowej ramki audio, w punktach. |
| width | **float** | Szerokość nowej ramki audio, w punktach. |
| height | **float** | Wysokość nowej ramki audio, w punktach. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wejściowy zawierający dane audio WAV do osadzenia. |

### Wartość zwracana

Nowo utworzony [IAudioFrame](../../iaudioframe/).

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) metoda

Tworzy nową ramkę audio i wstawia ją do kolekcji kształtów pod wskazanym indeksem, używając istniejącego obiektu audio z listy Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks rozpoczynający od zera, w którym należy wstawić ramkę audio. |
| x | **float** | Współrzędna x nowej ramki audio, w punktach. |
| y | **float** | Współrzędna y nowej ramki audio, w punktach. |
| width | **float** | Szerokość nowej ramki audio, w punktach. |
| height | **float** | Wysokość nowej ramki audio, w punktach. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Instancja [IAudio](../../iaudio/) z kolekcji Presentation.Audios do osadzenia. |

### Wartość zwracana

Nowo utworzony [IAudioFrame](../../iaudioframe/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAudioFrame](../../iaudioframe/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [IShapeCollection](../)
* Klasa [IAudio](../../iaudio/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)