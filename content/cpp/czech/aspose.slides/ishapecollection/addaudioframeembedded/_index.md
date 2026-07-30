---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří nový audio rámec s vloženým souborem WAV a přidá jej na konec kolekce tvarů. Vložený zvuk je přidán do kolekce Presentation.Audios.
type: docs
weight: 248
url: /cs/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metoda


Vytvoří nový audio rámec s vloženým souborem WAV a přidá jej na konec kolekce tvarů. Vložený zvuk je přidán do kolekce Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového audio rámce, v bodech. |
| y | **float** | Y-souřadnice nového audio rámce, v bodech. |
| width | **float** | Šířka nového audio rámce, v bodech. |
| height | **float** | Výška nového audio rámce, v bodech. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Vstupní proud obsahující data WAV audio k vložení. |

### Návratová hodnota

Nově vytvořený [IAudioFrame](../../iaudioframe/).

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) metoda


Vytvoří nový audio rámec a přidá jej na konec kolekce tvarů pomocí existujícího audio objektu ze seznamu Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice nového audio rámce, v bodech. |
| y | **float** | Y-souřadnice nového audio rámce, v bodech. |
| width | **float** | Šířka nového audio rámce, v bodech. |
| height | **float** | Výška nového audio rámce, v bodech. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Instance [IAudio](../../iaudio/) ze sbírky Presentation.Audios. |

### Návratová hodnota

Nově vytvořený [IAudioFrame](../../iaudioframe/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAudioFrame](../../iaudioframe/)
* Třída [Stream](../../../system.io/stream/)
* Třída [IShapeCollection](../)
* Třída [IAudio](../../iaudio/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)