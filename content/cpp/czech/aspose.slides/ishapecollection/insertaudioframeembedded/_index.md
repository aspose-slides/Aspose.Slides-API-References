---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides pro C++ – reference API
description: Vytvoří nový audio rámec s vloženým souborem WAV a vloží jej do kolekce tvarů na zadaném indexu. Vložený audio soubor je přidán do kolekce Presentation.Audios.
type: docs
weight: 261
url: /cs/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metoda

Vytvoří nový audio rámec s vloženým souborem WAV a vloží jej do kolekce tvarů na zadaném indexu. Vložený audio soubor je přidán do kolekce Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulově založený index, na kterém se má vložit audio rámec. |
| x | **float** | x-souřadnice nového audio rámce v bodech. |
| y | **float** | y-souřadnice nového audio rámce v bodech. |
| width | **float** | Šířka nového audio rámce v bodech. |
| height | **float** | Výška nového audio rámce v bodech. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Vstupní proud obsahující data WAV audia k vložení. |

### Návratová hodnota

Nově vytvořený [IAudioFrame](../../iaudioframe/).

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) metoda

Vytvoří nový audio rámec a vloží jej do kolekce tvarů na zadaném indexu pomocí existujícího audio objektu ze seznamu Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulově založený index, na kterém se má vložit audio rámec. |
| x | **float** | x-souřadnice nového audio rámce v bodech. |
| y | **float** | y-souřadnice nového audio rámce v bodech. |
| width | **float** | Šířka nového audio rámce v bodech. |
| height | **float** | Výška nového audio rámce v bodech. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Instance [IAudio](../../iaudio/) ze sbírky Presentation.Audios k vložení. |

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