---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy nową ramkę audio z osadzonym plikiem WAV i dodaje ją na koniec kolekcji kształtów. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios.
type: docs
weight: 248
url: /pl/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metoda


Tworzy nową ramkę dźwiękową z osadzonym plikiem WAV i dodaje ją na koniec kolekcji kształtów. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna x nowej ramki dźwiękowej, w punktach. |
| y | **float** | Współrzędna y nowej ramki dźwiękowej, w punktach. |
| width | **float** | Szerokość nowej ramki dźwiękowej, w punktach. |
| height | **float** | Wysokość nowej ramki dźwiękowej, w punktach. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wejściowy zawierający dane audio WAV do osadzenia. |

### Wartość zwracana

Nowo utworzony [IAudioFrame](../../iaudioframe/).

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) metoda


Tworzy nową ramkę dźwiękową i dodaje ją na koniec kolekcji kształtów, używając istniejącego obiektu audio z listy Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna x nowej ramki dźwiękowej, w punktach. |
| y | **float** | Współrzędna y nowej ramki dźwiękowej, w punktach. |
| width | **float** | Szerokość nowej ramki dźwiękowej, w punktach. |
| height | **float** | Wysokość nowej ramki dźwiękowej, w punktach. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Instancja [IAudio](../../iaudio/) z kolekcji Presentation.Audios. |

### Wartość zwracana

Nowo utworzony [IAudioFrame](../../iaudioframe/).

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IAudioFrame](../../iaudioframe/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [IShapeCollection](../)
* Klasa [IAudio](../../iaudio/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)