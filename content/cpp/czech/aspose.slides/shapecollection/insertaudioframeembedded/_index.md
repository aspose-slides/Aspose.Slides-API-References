---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides pro C++ API Reference
description: "Vytvoří nový audio rámec s vloženým souborem WAV a vloží jej do kolekce tvarů na zadaném indexu. Vložený zvuk je přidán do kolekce Presentation::get_Audios."
type: docs
weight: 300
url: /cs/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metoda

Vytvoří nový audio rámec s vloženým souborem WAV a vloží jej do kolekce tvarů na zadaném indexu. Vložený zvuk je přidán do kolekce [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na kterém se má vložit audio rámec. |
| x | **float** | X-souřadnice nového audio rámce, v bodech. |
| y | **float** | Y-souřadnice nového audio rámce, v bodech. |
| width | **float** | Šířka nového audio rámce, v bodech. |
| height | **float** | Výška nového audio rámce, v bodech. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Vstupní proud obsahující data zvuku WAV k vložení. |

### Návratová hodnota

Nově vytvořený [IAudioFrame](../../iaudioframe/).

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) metoda

Vytvoří nový audio rámec a vloží jej do kolekce tvarů na zadaném indexu pomocí existujícího audio objektu ze seznamu [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na kterém se má vložit audio rámec. |
| x | **float** | X-souřadnice nového audio rámce, v bodech. |
| y | **float** | Y-souřadnice nového audio rámce, v bodech. |
| width | **float** | Šířka nového audio rámce, v bodech. |
| height | **float** | Výška nového audio rámce, v bodech. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Instance [IAudio](../../iaudio/) ze sbírky [Presentation::get_Audios](../../presentation/get_audios/) k vložení. |

### Návratová hodnota

Nově vytvořený [IAudioFrame](../../iaudioframe/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAudioFrame](../../iaudioframe/)
* Třída [Stream](../../../system.io/stream/)
* Třída [ShapeCollection](../)
* Třída [IAudio](../../iaudio/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)